git init                     		创建一个git库
git status                   		查看工作区的状态
git diff		    				查看修改的内容
git add 带扩展名的文件名     		准备提交的文件
git commit -m "描述语"             	提交文件
git reset --hard 版本的commitID    	穿梭到指点版本
git log								查看提交历史
git reflog							查看命令历史
git checkout -- 文件名  			后退一步
git rm 文件名						删除暂存区的文件
git remote add origin github的ssh地址       关联远程库
git push -u origin master					第一次推送master分支的所有内容
git push origin master						推送master分支的所有内容
git clone 地址								克隆远程库
git checkout -b dev							创建并切换分支
git branch dev								创建分支
git checkout dev							切换分支
git branch									查看分支