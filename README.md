# V2RAY-BETA

OK，现在我们先输入 sudo -i 来切换到 root 用户，然后再输入下面的命令来安装 V2Ray

    bash <(curl -s -L https://git.io/v2ray.sh)

然后选择安装，即是输入 1 回车

选择传输协议，如果没有特别的需求，使用默认的 TCP 传输协议即可，直接回车
选择端口，如果没有特别的需求，使用默认的端口即可，直接回车
是否屏蔽广告，除非你真的需要，一般来说，直接回车即可

安装 V2Ray



是否配置 Shadowsocks ，如果不需要就直接回车，否则就输入 Y 回车
Shadowsocks 端口，密码，加密方式这些东西自己看情况配置即可，我个人当然是全部直接回车。。
OK，按回车继续

快速管理 V2Ray
v2ray info 查看 V2Ray 配置信息
v2ray config 修改 V2Ray 配置
v2ray link 生成 V2Ray 配置文件链接
v2ray infolink 生成 V2Ray 配置信息链接
v2ray qr 生成 V2Ray 配置二维码链接
v2ray ss 修改 Shadowsocks 配置
v2ray ssinfo 查看 Shadowsocks 配置信息
v2ray ssqr 生成 Shadowsocks 配置二维码链接
v2ray status 查看 V2Ray 运行状态
v2ray start 启动 V2Ray
v2ray stop 停止 V2Ray
v2ray restart 重启 V2Ray
v2ray log 查看 V2Ray 运行日志
v2ray update 更新 V2Ray
v2ray update.sh 更新 V2Ray 管理脚本
v2ray uninstall 卸载 V2Ray
