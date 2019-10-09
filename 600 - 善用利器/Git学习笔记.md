# Git 学习笔记

## 初学者流程

### Git配置

- 输入ssh-keygen –t rsa –C "abc@163.com"，ssh-keygen之间没有空格，其他的之间有空格。Enter。

- 出现页面为保存密钥路径，建议默认。

- 打开github.com，在Settings中找到SSH and GPG keys，然后new SSH key，自定义Title，将id_rsa.pub中内容粘贴到Key中。

- 验证是否配置成功，在git bash输入命令 ssh -T git@github.com，第一次配置会让你输入yes/no，输入yes。

- 配置用户名和邮箱

  - **git config** --global user.name "用户名"

  - git config --global user.email "邮箱"

    

### Git 托管

- **git init** ，初始化Git工作目录。
- 输入命令：**git remote** add origin git@github.com:plusru/exam.git，添加远程主机。
- 同步仓库内容，输入命令：**git pull** git@github:plusru/exam.git。
- 本地内容上传到仓库：
  - 执行增加命令：**git add**.，add后面的点，表示的是提交所有文件，如果想指定提交文件，可以写文件名。
  - 执行提交命令：**git commit** -m, "its commits"，-m后面是提示信息。
  - 推送：命令 **git push** git@github.com:plusru/exam.git

## Git远程操作



## 注意事项

### Git不能提交空目录

- git和 svn不同，仅仅跟踪文件的变动，不跟踪目录。

**解决方法：**

- 在目录下创建 .gitkeep 文件，在项目的 .gitinore中设置不忽略 .gitkeep





## 参考

[知乎]: https://zhuanlan.zhihu.com/p/23167699	"知乎博客"
[阮一峰的网络日志]: http://www.ruanyifeng.com/blog/2014/06/git_remote.html

