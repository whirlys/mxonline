#MxOnline

> 本项目的代码是 慕课网《[强力django+杀手级xadmin 打造上线标准的在线教育平台](http://coding.imooc.com/class/78.html)》


----

## 一些说明

代码根据安装指南操作是可以正常运行的，但是缺少视频播放页面，需要看课程视频自己添加视频播放页面的一点代码，之后我会添加上来

## 安装指南

1. 先安装mysql
   安装的时候需要密码设置为root

2. 通过navicat 新建数据库 库名为mxonline

3. navicat 导入sql文件

4. pip install -r requirements.txt 安装依赖包
5. http://www.lfd.uci.edu/~gohlke/pythonlibs/#mysql-python 下载 MySQL_python-1.2.5-cp27-none-win_amd64.whl
    然后pip install MySQL_python-1.2.5-cp27-none-win_amd64.whl 安装mysqldb驱动
6. python manage.py runserver

7. 浏览器中输入 127.0.0.1:8000访问