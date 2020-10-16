将本地文件夹提交到GitHub仓库：在GitHub创建一个同名空仓库，不勾选README.md。
绑定远程仓库（绑定完成后，即可将本地仓库提交到GitHub仓库）：（1）cd 文件夹
（2）git init：将文件夹初始化为一个git仓库（若初始化错误：将app文件夹初始化为git仓库，则要删除app文件夹下面的.git文件夹）
（3）绑定远程仓库：git remote -v；查看当前git仓库绑定的远程仓库
git remote add origin 仓库地址：绑定远程仓库（该命令可在空仓库页面教程中直接复制）
（如果绑定错误：执行git remote remove origin移除绑定）