拉取根目录下所有子模块程序，只限于更新到@地址的程序，不是最新的程序
git submodule update --force --init --recursive
更新子模块为最新的程序，拉取master下的最新程序
git pull origin master
git add .
git commit -m ""
git push
查看目录下调用了多少个子模块
git ls-files --recurse-submodules
