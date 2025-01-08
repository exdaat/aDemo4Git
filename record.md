# please read me

## Reference

```html
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
https://git-scm.com/book/en/v2
【给傻子的Git教程】https://www.bilibili.com/video/BV1Hkr7YYEh8?vd_source=2c5daa28b8873e7714e7d841e7991f29
https://stackoverflow.com/questions/783811/getting-git-to-work-with-a-proxy-server-fails-with-request-timed-out
https://blog.csdn.net/czjl6886/article/details/122129576
```

## Vscode Setting

打开VScode 左下角齿轮设置，设置
搜索git.path，在结果中打开 settings.json 文件
在其中git.path修改为："git.path": "C:\\Program Files\\Git\\cmd\\git.exe"
重启

## Your Identity

```bash

git config --global user.name "XinqiLiu"
git config --global user.email 2594025409@qq.com

```

## proxy

```bash
git config --global https.proxy http://127.0.0.1:7897

git config --global https.proxy https://127.0.0.1:7897

git config --global --unset http.proxy

git config --global --unset https.proxy
```

## git Remote
```
echo "# aDemo4Git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main


# git remote remove origin
git remote add origin https://github.com/exdaat/aDemo4Git.git

git push -u origin main
```

## Git Commit

```bash
git add .
git commit -m "Commit local changes before merge"
```

## Git Push

```bash
git remote add origin https://github.com/exdaat/aDemo4Git.git
git branch -M main
git push -u origin main
```

## Git Rename
在去Github修改项目名称后，

```bash
git remote remove git-demo
git remote set-url exdaat https://github.com/exdaat/aDemo4Git.git
git remote -v
git fetch exdaat
```

Quick setup — if you’ve done this kind of thing before
or	
https://github.com/exdaat/aDemo4Git.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# aDemo4Git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/exdaat/aDemo4Git.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/exdaat/aDemo4Git.git
git branch -M main
git push -u origin main