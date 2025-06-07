1、初始化仓库(git init)：在需要设置Git仓库的目录下输入git init进行仓库初始化，此时会生成.git文件夹

2、添加文件到暂存区(git add)：在git仓库目录输入git add . 将所有文件添加至暂存区，或输入(git add Git学习案例.md)将指定文件添加至暂存区

3、提交至本地仓库(git commit)：在git仓库目录输入git commit -m "Initial priject setup"，将所有暂存区的文件提交至本地仓库

4、连接远程仓库，若已连接则跳过该步骤(git remote add GitLearning git@github.com:RocFire/GitLearning.git )

5、推送至远程分支仓库(git push GetLearning origin)：可设置默认的git push推送远程分支(git remote --set-upsteam GitLearning origin)，此时可通过git push即可推送至远程origin分支中。

6、请求合并至主分支(pull request)






备注：
1、.git文件夹：git版本控制系统自动生成的相关快照信息等

2、.gitignore文件：忽略不需要进行版本控制的目录与文件，构建时自动生成的文件与临时文件，都不应纳入版本控制