建议 Windows 环境下使用 xelatex 编译. 若在其他环境下编译, 字体会稍有差别, 
可以安装 windows 字体后, 在文类的选项中添加 `fontset=windows`, 即

```
\documentclass[a4paper,zihao=-4,UTF8,fontset=windows,AutoFakeBold=2.85]{ctexart}
```
