# btpanel-v7.7.0

btpanel-v7.7.0-backup  官方原版v7.7.0版本面板备份

**Centos/Ubuntu/Debian安装命令 独立运行环境（py3.7）：**

```Bash
curl -sSO https://raw.githubusercontent.com/ninjabc/webpanel/main/install/install_panel.sh && bash install_panel.sh
```

# 面板优化

如需优化，可执行一键脚本

```
curl -sSO https://raw.githubusercontent.com/ninjabc/webpanel/main/one_key_happy/one_key_happy.sh && bash one_key_happy.sh
```

**如果遇到重启后宝塔乱码 请DD最新版Debian系统然后修改语言区域：**

```Bash
localectl set-locale LANG=en_US.UTF-8
nano /etc/default/locale
```

```Bash
LANG="en_US.UTF-8"
LC_ALL="en_US.UTF-8"
```

修改后保存文件，重启VPS即可。
