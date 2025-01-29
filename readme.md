# Onecloud-MCServer

玩客云的我的世界服务器



MC支持版本：1.8  1.12  1.17  1.18  1.19  1.20  1.20.4

------

1.检查你的java版本

```
java -version
```

若版本较低或干脆没有(~~菜~~)

```
apt install default-jre
```

(如果你的 apt 源不太 OK 的话，自行百度： apt换源  或者 

```
bash <(curl -sSL https://linuxmirrors.cn/main.sh)
```

)

2.下载这个仓库

```
git clone https://github.com/Lirzh/Onecloud-MCServer.git
```

(如果你的 git 源不太 OK 的话，自行百度： git换源  或者 

```
git clone https://bgithub.com/Lirzh/Onecloud-MCServer.git
```

)

3.切换的仓库文件夹

```
cd Onecloud-MCServer
cd Server-Version
```

4切换到你要的版本

```
cd <版本号>
```

例如我要玩 1.20.4

```
cd 1.20.4
```

5.启动

(偷偷告诉你：已经同意了用户协议并开启了盗版登录模式)

临时启动：

```
chmod 777 go.sh
./go.sh
```

后台运行：

```
screen -S Onecloud-MCServer
chmod 777 go.sh
./go.sh
```

维护请自行百度： screen 命令

6.Play

服务器地址：玩客云的IP地址:25565