1,安装git bash
2,进入git bash 获取秘钥   ssh-keygen-t rsa-C "注册git hub的邮箱"
3,秘钥在c盘用户目录下
4在github中setting找到ssh and gpg keys 完成秘钥注册

5,检查是否绑定成功 ssh -T git@github.com

git config --global user.name ""
git config --global user.email "自己的邮箱"

git status 查询状态
git add 提交到仓库
git commit -m ""备注"" 
git push 提交到github