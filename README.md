# Raspberry Pi3 - AP

下載 RaspberryPi3-AP.sh 到 rPi3，下載指令如下：

wget  https://raw.githubusercontent.com/shiehyaotsung/RaspberryPi3-AP/master/RaspberryPi3-AP.sh

執行安裝指令，格式如下：（密碼最少  8 碼）

sudo  bash RaspberryPi3-AP.sh   WiFi名稱   密碼

範例：

sudo  bash RaspberryPi3-AP.sh   rPi3   raspberry

或者如下格式：

sudo  bash RaspberryPi3-AP.sh   WiFi名稱   密碼  區域IP前3碼  區域IP最後一碼開頭  區域IP最後一碼結尾

範例：

sudo  bash RaspberryPi3-AP.sh   rPi3   raspberry  172.18.1  100  160

假設依範例成功執行之後，可用手機連上 wifi 帳號 rPi3 ，密碼 raspberry
用 google 上 myrpi3:4567 或 pi.rpi3.my:4567 的網頁你將看到 rPi3 IP : 192.168.1.105
你就可以用 putty 或 ssh 登入你的 rPi3 。
你的 arduino 也可以連上這 AP ，用 myrpi3 或 pi.rpi3.my 作為網址，將資料傳給你在 rPi3 的 IoT server 。
即使你 rPi3 的 IP 改變了，你也不須修改 arduino 程式裏的 IP 。
# ========================================================================================

Download RaspberryPi3-AP.sh 

wget  https://raw.githubusercontent.com/shiehyaotsung/RaspberryPi3-AP/master/RaspberryPi3-AP.sh

Please use WiFiName and password（minimum: 8 characters）

Usage:

sudo  bash RaspberryPi3-AP.sh   WiFiName   password

or :

sudo  bash RaspberryPi3-AP.sh   WiFiName   password  localIP  from  to

Example:

sudo  bash RaspberryPi3-AP.sh   rPi3   raspberry

or

sudo  bash RaspberryPi3-AP.sh   rPi3   raspberry  172.18.1  100  160


After connect to AP , you can browse myrpi3:4567 or pi.rpi3.my:4567 and you will get your rPi3 IP . 


