# mathinchem2020 Version 220106

化学中的数学2020年课程总结的说明文档

## 2022年1月16日更新

根据化学中的数学2021年课程，对该笔记的内容进行了适当的增添调整。

刘剑老师的思路是：以经典-量子对应为线索的四大对应关系。为此，将原有内容重排如下：

- Chapter 1：数学准备（原 Chapter 6）
- Chapter 2、3：Hamilton 力学与量子力学的算符形式（原 Chapter 1、7）
- Chapter 4、5：相空间与量子力学的相空间形式（原 Chapter 2、3、10）
- Chapter 6：Lagrange力学与量子力学的路径积分形式（原 Chapter 8）
- Chapter 7：量子力学的轨线形式——Bohm动力学（原 Chapter 9）
- Chapter 8：时间关联函数与光谱（原 Chapter 5）

其中，Chapter 5 在原 Chapter 10 Wigner函数的简介的基础上，扩充成为新的章节，因为该部分是2021年的授课重点之一。

相应的每章文件名改为`[number]_xxx.tex`，引文名称改为`ref_xxx.tex`。将引文名称去掉编号，是为了方便后续进行章节的重排。

## 文件结构

`main.tex` 中include了保存着每一个章节信息的 `chp_[number]_xxx.tex` 文件，其中为了方便定义了一些命令，可以参照定义简化latex文件的书写，若要更改每个章节的内容，编辑`chp_[number]_xxx.tex`  文件</u>。<u>如果要增添注释，请编辑 `ref_chp_[number].bib` 文件，同时修改对应的 `tex` 文件。

如果要查看 `pdf` ，需要按照如下顺序编译：`xelatex` 编译 `main.tex`，`bibtex` 编译对应的每个章节的 `.bib` 文件，最后再用 `xelatex` 编译两遍。 

`compile.sh` 是懒人脚本（Linux系统下
`compile.bat` 是懒人脚本（Windows系统下

章节安排：

- chapter 1 : Hamilton 运动方程
- chapter 2 : Liouville 定理
- chapter 3 : Liouville 方程
- chapter 4 : 多自由度的小振动
- chapter 5 : 时间关联函数
- chapter 6 : Gauss 积分的计算
- chapter 7 : Hamilton 力学与量子力学的算符形式
- chapter 8 : Lagrange 力学与量子力学的路径积分形式
- chapter 9 : Bohmain 动力学
- chapter 10 : Wigner 函数

`main.pdf` 是最终效果



