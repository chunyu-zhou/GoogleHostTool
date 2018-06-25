# GoogleHostTool
一键添加最新google hosts文件到本地hosts文件中，适用windows、linux、mac。我将最新的google hosts文件保存在远程服务器上，通过脚本下载获取最新hosts文件，并更新到本地hosts文件中。

## windows使用
- windows脚本采用powerShell编写
- 选中google-hosts.bat文件右键以管理员身份运行
- 遇到360等杀毒软件提示修改HOST，点击允许本次修改

## linux及Mac下使用
- 修改google-hosts.sh可执行权限,chmod u+x google-hosts.sh
- 配置软连接加入到全局环境中 ln -s 当前目录/google-hosts.sh /usr/bin/google-hosts
- 终端中输入google-hosts以root用户权限执行命令

## 注意
- 用户权限问题
- 部分linux系统中可能没有预装wget,需要手动先安装wget
- 执行完脚本后访问google,请记得是https://www.google.com.hk ,是https开头哦
- 如遇到执行完脚本后,google hosts不生效的问题请提交到issues

## 叨扰一下
- 因为在国内Host翻墙访问的特殊性，ZF在一些必要的时候会做一些特殊处理导致不能正常访问，为了国家发展和和平，请多理解。
- 您可以点击项目【Watch】 随时关注动态，我会在这里随时记录Host的实时可用性。

## 可用性记录
- 2018-6-19 - 2018-6-25  可用
- 2018-6-25 - 至今  不可用
