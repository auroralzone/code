" 显示中文帮助
set helplang=cn
if version >= 603
    set helplang=cn
    set encoding=utf-8
endif

" 设置字体
set guifont=Meslo\ LG\ S\ DZ\ Regular\ for\ Powerline:h13

" mac和linux系统将enc设置为utf-8
set enc=utf-8

" 设置外观 -------------------------------------
set number                      "显示行号
set showtabline=0               "隐藏顶部标签栏"
set guioptions-=r               "隐藏右侧滚动条"
set guioptions-=L               "隐藏左侧滚动条"
set guioptions-=b               "隐藏底部滚动条"
set cursorline                  "突出显示当前行"
set cursorcolumn                "突出显示当前列"
set langmenu=zh_CN.UTF-8        "显示中文菜单
" 变成辅助 -------------------------------------
syntax on                       "开启语法高亮
set nowrap                      "设置代码不折行"
set fileformat=unix             "设置以unix的格式保存文件"
set cindent                     "设置C样式的缩进格式"
set tabstop=4                   "一个 tab 显示出来是多少个空格，默认 8
set shiftwidth=4                "每一级缩进是多少个空格
set backspace+=indent,eol,start "set backspace&可以对其重置
set showmatch                   "显示匹配的括号"
set scrolloff=5                 "距离顶部和底部5行"
set laststatus=2                "命令行为两行"
" 其他杂项 -------------------------------------
set mouse=a                     "启用鼠标"
set selection=exclusive         "允许区域选择
set selectmode=mouse,key
set matchtime=5                 "短暂跳转到匹配括号的时间
set ignorecase                  "忽略大小写"
set incsearch                   "查询匹配单词，回车
set hlsearch                    "高亮搜索项"
set noexpandtab                 "不允许扩展table"
set whichwrap+=<,>,h,l          "能从行首或行尾跳到另一行
set autoread                    "当文件被外部改变时自动读取
