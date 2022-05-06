项目创建过程

一、检查是否安装：VueRouter
    使用： vue -V 命令查询

二、创建项目：
    Vue create Name（*kebab-case）使用 PascalCase 会报错

三、测试运行
    使用 npm run serve 运行下载的程序；也可以使用 yarn run serve 命令

四、检测是否被 git 仓库监测；并创建 git 网上仓库

    1、使用 git status 命令进行测试；如返回：
        On branch master
        nothing to commit,working tree clean
    则视为被监控；否则请使用 git init 命令进行创建 git 文件并进行监测

    2、先创建 git 仓库
    访问：`https://github.com/` gitHub 官方网站进行注册并登录；
    创建仓库后获取仓库的 API 接口；例：（https）://github.com/账号名/仓库名.git
    在后台使用：git remote add 简称（如：abc等） 仓库地址 ；的方式进行保存仓库；
    简称是用来方便后期保存时调用仓库链接；此处保存后，后期可以使用简称直接进行简写。

    3、使用 git remote -v 进行测试
    4、在使用 git push -u 简称 master；进行上传
    （master 主分支上；而此处的 -u 是为了保存当前 push 的地址；以后可以进行简写；使用 git push 即可）
