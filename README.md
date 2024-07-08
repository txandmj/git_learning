# git_learning
# 创建repository
- Home -> 右上方 “+” -> New repository -> creat repository 
- 电脑上建立文件夹用于存储repository, eg c:/code
- open git bash
- command: 
  - **cd c:** 进入c盘
  - **cd code:** 进入c盘下的code （可以输入 ls 查看code内的list)
  - **cd learn-python**: 进入c盘下的code内的learn-python. 这时可以用pycharm打开readme.md文件进行编辑
# 从github下载文件到本地机继续编辑
- 电脑上建立文件夹用于存储repository, eg c:/code
- open git bash
- command: 
  - **cd c:** 进入c盘
  - **cd code:** 进入c盘下的code （可以输入 ls 查看code内的list)
  - **cd learn-python**: 进入c盘下的code内的learn-python.
  -  **git checkout first-branch**： 根据实际情况选择pull哪一个分支
  - **git pull**：此时readme.md应该下载至c:/code/learn-python. 用pycharm打开readme.md文件进行编辑即可
   
# 将编辑过的readme.md 同步至github
- open git bash
- command: 
  - **git status:** 查看状态。红色显示： modified:   readme.md
  - **git add readme.md** : 添加操作
  - **git commit -m "WIP"** : 给提交的版本作标识
  - **git status:** nothing to commit, working tree clean
  - **git push :** 完成同步，可以去github查看确认
