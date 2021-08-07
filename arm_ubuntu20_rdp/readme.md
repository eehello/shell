文档备份：https://hostloc.com/thread-871447-1-1.html

本脚本暂只支持Ubuntu20.

仅在ARM架构进行常规测试,不保证完全可用,请提前做好回滚准备!

甲骨文封号机制不明,不保证账号稳定性!

环境: LXDE + XRDP + XRDP-PA

个人自用截图(主题选择+设置背景+设置LXDE桌面环境完整中文支持.配置过程全GUI操作,无命令行,不额外安装其他配置软件):

安装命令:

    screen -S u2ad
    wget https://gist.githubusercontent.com/flyqie/60a005535afc0b5d45255619299b9630/raw/fa54bccd0dad4fb488b79ffdf0d3afeb17daf4c1/ubuntu-20-arm-desktop.sh -O ubuntu-20-arm-desktop.sh ; sudo bash ubuntu-20-arm-desktop.sh | tee -a ubuntu-20-arm-desktop.log
    # 一切确认无误后重启
    sudo reboot




待重启后即可通过SSH隧道访问,如需公网访问请自行开放防火墙.

    RDP Port: 3389
    RDP Username: rdpuser
    RDP Default Password: rdpuser_password
    请在安装后及时修改密码!



Github Gist链接:
https://gist.github.com/flyqie/60a005535afc0b5d45255619299b9630

参考链接:
https://gist.github.com/rkttu/35ecab5604c9ddc356b0af4644d5a226

https://gist.github.com/CraigCottingham/fad000cc2ec4678203acf62c4ad2ab23

https://github.com/MeowLove/Linux-Remote-Desktop-Environment

https://github.com/neutrinolabs/pulseaudio-module-xrdp/issues/44
