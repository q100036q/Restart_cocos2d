Restart_cocos2d
===============

To learn the cocos2d-x
 github 常见步骤如下： 1 git pull (从github上把代码pull下来并和本地合并) 2 git add . （添加,更新） 3 git add -A (删除文件了才使用) 4 git commit -m 'message' (提交到本地库) 5 git push (千万不要git push --force,这是强置push导致覆盖服务器的数据变得和本地一模一样，并须先git pull)6.如果你删除一个文件从工作树,然后提交删除:
git commit -a -m "A file was deleted"
上游,推动您的提交:
git push
