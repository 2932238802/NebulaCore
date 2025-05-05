## ssh密钥本地配置

- 检查现有ssh密钥
ls -al ~/.ssh

- 生成密钥
ssh-keygen -t ed25519 -C "2932238802@qq.com"

- 添加到 github
cat ~/.ssh/id_ed25519.pub
然后手动复制输出的所有内容（从 ssh-ed25519 开始，到你的邮箱或注释结束）。
登录你的 Git 托管服务网站（GitHub, GitLab, Gitee 等），找到 SSH 密钥设置页面，将复制的公钥内容粘贴进去并保存。

- 检查远端是不是 ssh
git remote -v

- 改成ssh
git remote set-url origin git@github.com:YourUsername/LosShell.git
注意这里是冒号
