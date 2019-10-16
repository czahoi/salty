说一下
逗比由于不可抗拒原因所导致ssrmu.sh脚本部分失效，本人进行修复。
原ssrmu.sh脚本地址：https://github.com/ToyoDAdoubiBackup/doubi

主要失效部分
1、ss/ssr qr link（二维码失效）
2、网络和密码学库（libsodium）安装失败
3、不支持centos7自动放行端口
4、centos bbr安装失败
5、部分link失效
6、部分资源失效
7、还有些记不清了.....

修复情况
1、ss/ssr qr link（二维码失效    已修复（更换为我自己的qr，qr地址：https://qr.salty.ml）
2、网络和密码学库（libsodium）安装失败    已修复（替换为官网版本）
3、不支持centos7自动放行端口    已修复（重写防火墙的部分）
4、centos bbr安装失败    已修复（替换为秋水逸冰的脚本，并重写bbr部分，秋水bbr地址：https://teddysun.com/489.html）
5、部分link失效    已修复（替换为我自己的地址）
6、部分资源失效    已修复（替换为我自己的地址）

BUG
1、不支持centos6自动放行端口

部分资源存放在我自己的网盘
如不放心可将脚本内地址替换为自己的地址
ps:部分资源指ssr主程序和jq解析器和管理脚本

逗比的ssr主程序下载地址：https://github.com/ToyoDAdoubiBackup/shadowsocksr
