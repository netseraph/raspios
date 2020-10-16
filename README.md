# Raspberry Pi OS源
 更换Raspberry Pi OS源

安装中文字体
sudo apt-get install ttf-wqy-zenhei

 

安装拼音

sudo apt-get install scim-pinyin

 

安装RDP远程桌面，不带desktop的系统不需要
sudo apt-get install xrdp

搜索无线信号
sudo iwlist scan |grep ESSID


sudo raspi-config
设置wifi
network Options
增加中文支持
change_locale

更新raspi-config，扩容SD卡，设置语言为：EN-US.UTF8 ZH-CN.UTF8，去掉EN-GB



#安装CA证书
sudo apt-get install ca-certifacates

#同步时间
sudo apt-get install ntpdate
sudo ntpdate -u ntp.ubuntu.com