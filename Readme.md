![Shadowsocks](https://github.com/teddysun/shadowsocks_install/raw/master/shadowsocks.png)
# Auto install Shadowsocks Server

shadowsocks.sh
===============
- Description: Auto Install Shadowsocks(Python) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/342.html

shadowsocks-libev.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for CentOS
- Intro: https://teddysun.com/357.html

shadowsocks-libev-debian.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
- Intro: https://teddysun.com/358.html

shadowsocks-go.sh
===============
- Description: Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/392.html

shadowsocks-crond.sh
===============
- Description: Check Shadowsocks(All version) Server is running or not, and start it if not running
- Intro: https://shadowsocks.be/6.html

shadowsocksR.sh
===============
- Description: Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
- Intro: https://shadowsocks.be/9.html

shadowsocks-all.sh
==================
- Description: Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/486.html
-【使用方法】
-使用root用户登录，运行以下命令：
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
-【卸载方法】
-若已安装多个版本，则卸载时也需多次运行（每次卸载一种）
-使用root用户登录，运行以下命令：
./shadowsocks-all.sh uninstall

haproxy.sh
===============
- Description: Auto Install haproxy for Shadowsocks Server
- Intro: https://shadowsocks.be/10.html

Copyright (C) 2014-2017 Teddysun <i@teddysun.com>
