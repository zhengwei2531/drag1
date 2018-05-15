# git使用
######注意
	1. master是项目主分支(默认)；
	2. git 的3个区：a=>b=>c
		a.工作区:项目的这块
		b.暂存区:帮我们保存的
			作为过渡层，避免误操作，保护工作区和版本区，分支处理
		c.版本区(库):
###git使用完整步骤
####1. git clone https://github.com/zhengwei2531/drag1.git 把GitHub上的项目克隆到本地
####2. cd进入项目目录，设置用户名邮箱(最后如果不加内容即查看)
	git config --global user.name "zhengwei2531"
	git config --global user.email "xxx"
######2.1. git config --list是查看git下的所有配置
