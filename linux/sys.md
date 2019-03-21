## sys

### Softwares

#### [gtags](https://www.gnu.org/software/global/global.html)

1. [Download](https://www.gnu.org/software/global/download.html) and extract
2. Install
```bash
./configure && make && make install
```

### Tips

1. emerge using proxy
```bash
# add proxy in /etc/portage/make.conf
http_proxy="http://localhost:8080"
https_proxy="https://localhost:8080"
```

2. scp windows to linux
```bash
scp -P 7777 src.file username@localhost:~/path/dest.file
```

3. ssh windows to linux
```bash
ssh -l username -p 7777 localhost
```

4. set alias in linux
```bash
alias ll='ls -l'
alias la='ls -la'
```

