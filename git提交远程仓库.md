# git提交远程仓库

* 在对应的可视化git工具中创建仓库

* 在本地项目下初始化仓库

  * 初始化仓库

    ```
    git init
    ```

  * 添加到本地仓库

    ```
    git add .
    ```

  * 提交到本地仓库

    ```
    git commit -m 'first commit'
    ```

  * 添加远程仓库

    ```
    git remote add origin <项目地址>
    ```

    注：项目地址 === ssh://git@gitlab.baijcn.com:2224/xutai/vueac.git 这种类型的

  * 推送到远程仓库

    ```
    git push -u origin master
    ```