### Tips

1. The using of [gen_tags.vim](https://github.com/jsfaint/gen_tags.vim)

Ensure [gtags](sys.md#gtags) already installed.

```bash
:GenGTAGS   # gererate GTAGS file
:ClearGTAGS # remove GTAGS file

Ctrl+\ c    # find functions calling this function
Ctrl+\ d    # find functions called by this function
Ctrl+\ e    # find this egrep pattern
Ctrl+\ f    # find this file
Ctrl+\ g    # find this definition
Ctrl+\ i    # find files #including this file
Ctrl+\ s    # find this C symbol
Ctrl+\ t    # find this text string
```

### Questions

1. Not an editor command: ^M

Reason: Because of the different line endings between DOS and Unix

Solution: [dos2unit](https://wiki.gentoo.org/wiki/Dos2unix)

```bash
# installation
emerge --ask app-text/dos2unix
# dos -> unix
dos2unix dos_file.txt
# unix -> dos
unix2dos unix_file.txt
```

### References
[My vimrc](https://github.com/zhenxiaoyuan/dotfiles/blob/master/vim/vimrc)