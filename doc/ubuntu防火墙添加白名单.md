
ufw enable/disable：打开/关闭ufw

ufw status：查看已经定义的ufw规则

ufw default allow/deny：外来访问默认允许/拒绝

ufw allow/deny 20：允许/拒绝访问20端口，20后可跟/tcp或/udp，表示tcp或udp封包。

sudo ufw allow proto tcp from 192.168.0.0/24 to any port 22：允许自192.168.0.0/24的tcp封包访问本机的22端口。

ufw delete allow/deny 20：删除以前定义的"允许/拒绝访问20端口"的规则


sudo ufw allow from 64.63.62.61

sudo ufw allow from 101.71.100.0/24
sudo ufw allow from 101.71.101.0/24
sudo ufw allow from 101.71.105.0/24
sudo ufw allow from 101.91.91.0/24
sudo ufw allow from 111.20.28.0/24
sudo ufw allow from 111.20.29.0/24
sudo ufw allow from 113.200.123.0/24
sudo ufw allow from 113.201.154.0/24
sudo ufw allow from 113.219.202.0/24
sudo ufw allow from 113.96.246.0/24
