# Django

#### 1.虚拟环境搭建

##### a.安装虚拟环境命令

- sudo pip intall virtualenv
- Sudo pip intall virtualenvwrapper

配置环境变量

创建目录用来存放虚拟环境

- mkdir $HOME/ .virtualenvs

打开../bashrc文件，添加如下

- export WORKON_HOME=$HOME/.virtualenvs
- source /usr/local/bin/virtualenvwrapper.sh

运行

- souce ~/.bashrc

##### b.使用虚拟环境

在python3中创建虚拟环境

- mkvirtualenv -p python3 py3_ivanka_1

##### c.虚拟环境的命令

查询命令

- workon
- workon py3_ivank_1

推出虚拟环境

- deactivate

删除虚拟环境

- revirtualenv py3_ivanka_1

##### d.虚拟环境中安装工具包

python3 版本下安装Django 4.2

pip install DJango==4.2

#### 2.创建Django项目

创建Django项目

- Django-admin startproject name

创建子应用

- python manager py startapp name