# Onecloud-MCServer

MC支持版本：1.8

------

1.检查你的java版本

```
java -version
```

若低于java8或干脆没有(~~菜~~)

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
```

4.启动

临时启动：

1.8：

```
java -server -jar 1.8-server.jar nogui
```

后台运行：

1.8：

```
screen -S Onecloud-MCServer
java -server -jar 1.8-server.jar nogui
```

维护请自行百度： screen 命令

5. Play

   服务器地址：玩客云的IP地址:25565