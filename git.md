##### 工作区->缓存区->远程仓库

##### 1.git上传

A.工作区上传到缓存区仓库

- git add .

A.工作区撤销更改

- git checkout 文件名

B.缓存区上传到远程仓库

- git commit -m

B.缓存区退回到工作区

- git reset HEAD 文件名

C.查看文件状态

- git status

C.查看日志

- git log

##### 2.版本回退

A.退回指定版本

- git reflog
- get reset --hard 版本号

A.退回上个版本，一个^代表会退一个版本

- get reset --hard HEAD^

##### 3.远程仓库

A.克隆

- git clone github地址

B.创建用户名、邮箱

- git config user.name 名字

- git config user.email 邮箱



echo "# IvankaSiss" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ivanka2025/IvankaSiss.git
git push -u origin main



echo "# IvankaSiss" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ivanka2025/IvankaSiss.git
git push -u origin main