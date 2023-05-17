### 个人门户网站 | Personal portal

主要作为个人信息的导航页，更方便快捷地访问的本人的各个社交网站，目前包含 github 和 leetcode 个人主页，后续会添加 个人公众号，个人网站以及一些个人作品网站等等。
--- 
It is mainly used as a navigation page for personal information, which makes it more convenient and quick to visit my various social networking sites, including github and leetcode personal homepage at present, and personal public account, personal website and some personal works websites will be added later.


欢迎访问 [portal](http://baixuran.cn/)
---
Welcome to [portal](http://baixuran.cn/)

### 部署 | deploy 

- 本网站是纯静态前端页面，需要通过静态服务器进行部署
- 可以通过 nginx 进行部署
  1. 项目文件夹复制到 /usr/share/nginx/html 目录下面
  2. 在 将 nginx.conf 文件复制到 /etc/nginx/conf.d/ 目录下面
  3. 启动 nginx ，或者 重新加载一下 nginx.conf 文件
- 可以通过 docker 进行部署
  1. 安装好 docker，自行百度
  2. 启动 docker 
    ```bash
    docker run -d -p 80:80 geekersmallwhite/portal:latest
    ```
- 访问本机 80 端口，`localhost:80 \ localhost`，即可看到效果

--- 
- This website is a static front-end page that needs to be deployed on a static server
- Can be deployed through nginx
1. Copy the project folder to the /usr/share/nginx/html directory
2. Copy the nginx.conf file to the /etc/nginx.conf.d/directory
3. Start nginx or reload the nginx.conf file
- Can be deployed through docker
1. Install docker and search Baidu by yourself
2. Start docker
```bash
docker run -d -p 80:80 geekersmallwhite/portal:latest
```
- Access the local port 80, 'localhost:80 \ localhost', you can see the effect


### Q&A

本网站参考其他开源项目，改编完成，如有问题，欢迎提出 issue
--- 
This website has been adapted by reference to other open source projects. If you have any questions, please feel free to raise your questions


> 欢迎联系我的个人邮箱 mandelgiegie@gmail.com 
> Welcome to contact my personal email

