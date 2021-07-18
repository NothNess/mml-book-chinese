# mml-book-chinese

这是[mml-book](https://github.com/mml-book/mml-book.github.io)项目的中文版本

翻译水平有限, 错误在所难免, 欢迎堪误

排版可能和原书有所不同, 我尽量贴近原书的排版

## 快速开始

如何从LaTex源码编译得到pdf? 使用以下命令:

```shell
git clone https://github.com/NothNess/mml-book-chinese
cd mml-book-chinese
xelatex main.tex
```

如果没有xelatex命令, 请先安装LaTex:

```
sudo pacman -S texlive-most texlive-langchinese # on Arch/Manjaro, 其他平台自行google
```

这时候目录下会出现`main.pdf`文件, 就是最终的pdf了

