# TaxiTrajectory-website
大学生创新大赛 基于出租车轨迹的医院选址分析 网站
## 部署方法
1. 下载或克隆本项目<br>
    * 将本项目的develop下载到指定文件夹并解压即可<br>
    * 或在本地执行以下命令<br>
    ```Bash
    git clone https://github.com/CS-Tao/TaxiTrajectory-website.git
    ```
    克隆本项目<br>
    ```Bash
    git pull origin develop
    ```
    拉取并合并develop分支<br>
2. 导航至本项目文件夹`TaxiTrajectory-website`或`TaxiTrajectory-website-develop`中并执行<br>
    ```Bash
    npm install
    ```
    安装依赖项<br>
3. 导航至本文件夹中的的子文件夹`bin`中并执行<br>
    ```Bash
    node www
    ```
    启动本服务<br>
4. 在本地浏览器中输入<br>
    ```Bash
    http://localhost:3000/
    ```
    进行测试<br>
    如果出现Express界面则成功
