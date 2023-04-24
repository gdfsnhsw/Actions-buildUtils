# Actions-buildUtils
[![](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmzzsfy%2FActions-buildUtils&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://github.com/mzzsfy)

一些通用的白嫖git Actions的构建工具  

## 使用教程

### 填写参数

fork本仓库 ( **⚠️ 如果你需要长期或者大量的使用Actions,请使用非fork方法,见后文,因为 GitHub 会根据此上游存储库计算您的 fork GitHub Actions 使用情况，这可能会导致此上游存储库被 GitHub 员工（如 MagiskOnWSA）禁用** )

按如下操作添加参数
![image](https://user-images.githubusercontent.com/43053461/204208295-4004ee4a-30dc-4e7f-9587-5c8f9edb52cd.png)

重要参数 
- `DOCKER_HUB_USERNAME` docker-hub 用户名
- `DOCKER_HUB_ACCESS_TOKEN` docker-hub 读写权限token或者密码,建议使用token

### 构建

按如下步骤点击

![image](https://user-images.githubusercontent.com/43053461/204227942-2f79ba80-f000-41cd-9b3a-a5b0f543e390.png)
![image](https://user-images.githubusercontent.com/43053461/204228180-34b77c57-05f8-4707-bf7e-02d75b6b315e.png)

快乐白嫖,记得给我点个star https://github.com/mzzsfy/Actions-buildUtils

### 私有库用法

github: 
首先创建token
https://github.com/settings/tokens/new

git地址写法`https://oauth2:<token>@github.com/name/repo`

其它git服务

git地址写法`https://<username>:<password>@<url>`

## 非fork同步本仓库

因为 GitHub 会根据此上游存储库计算您的 fork GitHub Actions 使用情况，这可能会导致此上游存储库被 GitHub 员工（如 MagiskOnWSA）禁用  
所以你如果你需要长期或者大量的使用Actions,请不要使用fork

使用导入
![image](https://user-images.githubusercontent.com/43053461/233926542-62677cc0-036c-4c64-8f16-47c26db3ea9f.png)
填入本仓库地址
![image](https://user-images.githubusercontent.com/43053461/233927154-d7f7e941-a569-4836-8946-6f1c13cc0cc3.png)
开启Actions
![image](https://user-images.githubusercontent.com/43053461/233927826-aaa1ff17-df06-4989-bec9-f59df6b80dac.png)

