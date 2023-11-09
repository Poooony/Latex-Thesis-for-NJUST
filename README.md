# LaTeX-Thesis-for-NJUST

本模板目前为学士学位论文而设置，如有硕士或博士有需求，请自行更改相关内容

由于本人并非本校硕士或博士，故无可靠来源确定硕士论文与博士论文的格式要求，恕无法提供硕士与博士论文的修改版

本模板基于[前人所作](https://github.com/jiec827/njustThesis)经修改而成，具体内容如下

1. 将[/sty/njustThesis.cls](https://github.com/jiec827/njustThesis/blob/master/sty/njustThesis.cls)中的`/CTEXunderline`更改为`/CJKunderline`以适应CTEX新版变化

2. 根据教务处最新2024年”南京理工大学学士论文撰写格式“文件而修改，将“学士学位论文“字体由宋体更改为方正魏碑，数字与字母默认启用Times New Roman字体

   注意：电脑中需装有方正魏碑字体才可保证正常显示，文件名为`FZWBJW.TTF`，如无，请自行安装

3. 开启AutoFakeBold，封面字体默认加粗，如无需要，请自行删除`\bold`部分

4. 封面添加学号部分

5. 脚注默认为带圈数字样式，如需改为默认样式，删除myThesis.tex文件中的以下部分即可

   ```
   \usepackage{pifont}
   \usepackage[perpage,symbol*]{footmisc}
   \DefineFNsymbols{circled}{{\ding{192}}{\ding{193}}{\ding{194}}
   	{\ding{195}}{\ding{196}}{\ding{197}}{\ding{198}}{\ding{199}}{\ding{200}}{\ding{201}}}
   \setfnsymbol{circled}
   ```

6. 其他细节微调

感谢[jiec827 (Jie Cheng)](https://github.com/jiec827)和[其他人](https://code.google.com/archive/p/latex-njust808/)对模板的贡献，没有他们，这个项目是不可能做成的

由于本人第一次使用LaTeX与git，并第一次编写readme，难免会有疏忽，敬请指正

***

2023.11.10 仓库中添加方正魏碑字体

