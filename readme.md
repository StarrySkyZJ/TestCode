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