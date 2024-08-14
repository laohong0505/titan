首先是L2脚本：

wget -O [titan-network.sh](http://titan-network.sh/) https://raw.githubusercontent.com/breaddog100/titan-network/main/titan-network-v2.sh && chmod +x [titan-network.sh](http://titan-network.sh/) && ./titan-network.sh

复制全部，然后链接vps，复制链接然后粘贴在ssh里执行即可。对比官方的手搓，更加简单，然后还加入了自动进程守护，方便掉线了自己重启。（但是依旧存在掉线几率，自己时不时看看）
