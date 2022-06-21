|                         Git常用命令                          |                           作用                           |
| :----------------------------------------------------------: | :------------------------------------------------------: |
|                        git --version                         |                       查看git版本                        |
|             git config --global user.name 用户名             |                       设置用户签名                       |
|             git config --global user.email 邮箱              |                       设置用户签名                       |
|                      git config --list                       |                   查看git配置文件信息                    |
|                       cat ~/.gitconfig                       |                   查看git配置文件信息                    |
|                           git init                           |                       初始化本地库                       |
|                          git status                          |                      查看本地库状态                      |
|                        git add 文件名                        |                       添加到暂存区                       |
|               git commit -m “日志信息” 文件名                |                       提交到本地库                       |
|                           git log                            | 查看commit的详细信息，但是不能察看已经删除了的commit记录 |
|                          git reflog                          |                查看所有分支的所有历史记录                |
|                   git reset --hard 版本号                    |                         版本穿梭                         |
|                    git reset --hard HEAD                     |                  回退到当前（指针）版本                  |
|                       git diff 文件名                        |             将工作区中的文件和暂存区进行比较             |
|              git diff 本地库中历史版本  文件名               |           将工作区中的文件和本地库历史记录比较           |
|                        git branch -v                         |                         查看分支                         |
|                      git branch 分支名                       |                         创建分支                         |
|                     git checkout 分支名                      |                         切换分支                         |
|                       git merge 分支名                       |               把指定的分支合并到当前分支上               |
|                        git remote -v                         |                 查看当前所有远程地址别名                 |
|                 git remote add 别名 远程地址                 |                          起别名                          |
| git remote set-url 别名 https://自己的token@github.com/github的用户名/仓库名.git |                 推送前用token登录GitHub                  |
|                     git push 别名 分支名                     |              推送本地分支上的内容到远程仓库              |
|                      git clone 远程地址                      |                将远程仓库的内容克隆到本地                |
|              git pull 远程库地址别名 远程分支名              | 将远程仓库对于分支最新内容拉下来后与当前本地分支直接合并 |
