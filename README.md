# .vimrc


"混用系统粘贴版

set clipboard=unnamed

"显示标尺

set ruler

"显示相对行号

set relativenumber

"编码

set encoding=utf-8

"插入和视图模式时鼠标可用

set mouse=iv

"需要 Vim iMproved 版本

set nocompatible

"根据文件名检测文件类型，以便能进行智能自动缩进等操作。

filetype indent plugin on

"开启语法高亮

syntax on

"更好的命令行补全

set wildmenu

"除了当使用大写字母时使用大小写无关查找

set ignorecase

set smartcase

"当新开一行时，如果没有开启文件特定的缩进规则

"则缩进保持与你当前行一致

set autoindent

"在左侧显示行号

set number

"缩进选项，根据个人偏好进行修改

"每个 TAB 的可视空格数

set tabstop=4

"编辑时 TAB 对应的空格数

set softtabstop=4

"当使用缩进操作 (>> 和 <<) 时缩进的空格数

set shiftwidth=4

"将 TAB 转换成空格

set expandtab

"为缩进和对齐开启智能化的 TAB 和空格切换功能

set smarttab
