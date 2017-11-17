# .vim
My Vim setup using Pathogen as a package manager. It does not use submodules yet. I designed it to be "plug-and-play". That is also why I chose Pathogen as a package manager, it required nothing from the user. 

## Installation
Download the package and place it in /home/$YOUR_USERNAME/.vim and then copy the .vimrc file into /home/$yourusername/ on Ubuntu and if you're using the Windows 10 Ubuntu Kernel.

```
cd /home/$YOUR_USERNAME
git clone "https://github.com/Sceluswe/.vim/"
cp /home/$YOUR_USERNAME/.vim/.vimrc /home/$YOUR_USERNAME/
```

## Packages
https://vimawesome.com/plugin/delimitmate

https://vimawesome.com/plugin/nerdtree-red

https://vimawesome.com/plugin/onedark-vim

https://vimawesome.com/plugin/syntastic

https://vimawesome.com/plugin/tcomment

https://vimawesome.com/plugin/vim-airline-themes

https://vimawesome.com/plugin/vim-airline

https://vimawesome.com/plugin/fugitive-vim

https://vimawesome.com/plugin/vim-gitgutter

## Modifications
The .vimrc file contains some of my prefered modifications and additional fixes that were relevant in my case.

## Result
![Imgur](https://i.imgur.com/Qv5VYnU.png)

## Future improvements
1. Change the airline and tabline to fit the overall style better.
2. Add full mouse support.

## Fixed Issues
- Find out why the syntax checker currently doesn't work, fix it.
    - jshint was missing.
