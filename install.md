For windows

```powershell
winget install vim.vim

```
You can also access this [site](https://www.vim.org/download.php) to install manually.

For debian

```shell
apt-get install vim -y
```

Edit the configuration file
```shell
vim ~/.vimrc
```

```
" Automatic Line Wrapping
set textwidth=80		" Maximum 80 characters per line
set formatoptions+=t		" Auto-wrap text using textwidth
set formatoptions+=c		" Auto-wrap comments
set formatoptions+=q		" Allow formatting of comments with "gq"
set formatoptions+=r		" Automatically insert comment leader after hitting <Enter>
set formatoptions+=o		" Automatically insert comment leader after 'o' or 'O'

" Display & UI Settings
set wrap			" Enable visual line wrapping
set linebreak			" Break lines at appropriate characters (don't break words)
syntax on			" Enable syntax highlighting
set number			" Show line numbers
set hlsearch			" Highlight search results (use :nohlsearch to clear)
```
