# Git 学习笔记











## Others

### Git不能提交空目录

- git和 svn不同，仅仅跟踪文件的变动，不跟踪目录。

**解决方法：**

- 在目录下创建 .gitkeep 文件，在项目的 .gitinore中设置不忽略 .gitkeep

