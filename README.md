# 贴吧云签到云回复(修改为sqlite数据库,方便快捷安装)


## 项目安装教程

## 1.安装python模块


```shell
pip install -r requirements.txt
```
### 2.生成django的数据库

```shell
python manage.py makemigrations
python manage.py migrate
```

### 3.按照提示创建管理员账号

```shell
python manage.py createsuperuser
```
### 4.运行django的web服务
```shell
默认：
    python manage.py runserver
可选（指定端口）：
    python manage.py runserver 0.0.0.0:8888
```
### 5.运行项目目录下的task.py文件
```shell
python task.py
```
### 6.搭建完成，打开网站查看
```shell
管理员界面：http://127.0.0.1:8000/admin
首页扫码登陆：http://127.0.0.1:8000

```
