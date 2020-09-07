## 当前项目的说明书

    git操作的具体步骤
        1、cd 路径 （进入当前目录）
        2、配置git基本操作
            git config --global user.name "StarrySkyZJ"
            git config --global user.email "996508140@qq.com"
        3、git init （在本地进行初始化，建立暂存区）
            .git 文件存储当前项目的所有版本信息
        4、工作区 ==> 暂存区
            git add 文件名
            git add * 提交所有文件
            git commit -m "这一次提交的描述"
        5、查看当前工作区的状态
            git status
        6、从暂存区恢复文件到工作区
            git checkout 文件名
        7、查看工作区和暂存区版本的区别
            git diff
        8、查看已经提交到暂存区的历史版本
            git log
        9、恢复到指定的版本
            git reset --hard 版本号
        10、生成ssh密匙 暂存区==>远程仓库
            ssh-keygen -t rsa -C "996508140@qq.com";

        密匙目录：C:\Users\zhoujian\.ssh\id_rsa.pub

        11、github账户配置密匙

        12、暂存区==>远程仓库