# Github-Plugin

适用于Yunzai-V3及其衍生机器人框架的Github事件推送插件

使Yunzai-v3系列机器人能够接收到**自己和自己所在组织中具有Admin权限**的仓库的更新。基于Github的Webhook功能。

感谢 @ikechan8370 大佬的原作，本插件基于他的代码进行改进，调整和补充。

## 安装教程 💡

请将Github-Plugin放置在Yunzai-Bot的plugins目录下，重启Yunzai-Bot后即可使用。

1. 推荐使用git进行安装，以方便后续升级。在Yunzai目录打开终端，运行

- 使用github (国外服务器推荐)
```sh
git clone https://github.com/jiangyin14/github-plugin.git ./plugins/github-plugin
```
- 使用ghproxy (国内服务器推荐)
```sh
git clone https://mirror.ghproxy.com/https://github.com/jiangyin14/github-plugin.git ./plugins/github-plugin
```

2. 安装依赖

```sh
pnpm install
```

然后添加一个webhook，大概是`http://[ip]:[端口号默认59008]/github-webhook`

<img width="1148" alt="image" src="https://user-images.githubusercontent.com/21212372/228236286-24384e83-aded-4fcc-ba61-1e1eb241aaa1.png">


根据情况选是所有事件还是只有push

别的自己看吧！
