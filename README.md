# NeoVim configuration

### installation
```bash
# for mac
brew install neovim # usinging homebrew

# for ubuntu
sudo snap install nvim --classic # using snap
export PATH=$PATH:/snap/bin
source ~/.bashrc

# clone my nvim configuation
git clone https://github.com/MetythornPenn/neovim-config.git ~/.config/nvim
# open nvim
nvim
```

### basic vim command 
```bash
# leave vim
:q 

# leave without save change
:q!

# write and quite
:wq

# write change to the file 
:w 

# insert model
i : insert between line 
a : insert to the next char of the line 
o : insert below the current line 
I : insert to the begining of the line 
A : insert to the end of the line 
O : insert new line above the current line 

# set line number
:set number 

# using mouse 
:set mouse=a 

# set colorscheme 
:colorscheme slate

# config on .vimrc
vi ~/.vimrc
set number
set relativenumber
set tabstop=4
set shiftwidth=4
set autoindent
set mouse=a
colorscheme slate



# move n time up/donw
5 + cursor up : move 5 line up 
3 + cursor down : move 3 line down 

# key map 
h : move left 
l : move right 
j : move down 
k : move up 

# undo 
u 

# redo 
control + r 

# insert visual mode 
v 

# copy 
y 

# paste 
p 

# delete 
d 

# delete the whole line 
dd 

# delete all content and go to insert mode 
cc 

# delete all content next to the cursor 
D 

# delete in a word 
diw 

# change in a word 
ciw 

# move to the top line 
gg 

# move to the last line 
G 

# tab or indent right 
>>

# indent left 
<<



```

### Reference

- [youtube tutorial to config nvim](https://www.youtube.com/watch?v=4zyZ3sw_ulc&list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn&index=4)
- [github for nvim config](https://github.com/cpow/neovim-for-newbs)
- [vim tutorial](https://www.youtube.jcom/watch?v=RZ4p-saaQkc&t=2889s)
- [dev environtment from Josean](https://github.com/josean-dev/dev-environment-files?tab=readme-ov-file)
