## gdb

### Tips

```bash
finish  # 结束函数
return  # 直接返回，可以使用该方式直接从循环函数中返回

bt      # 列出堆栈信息
frame   # 查看当前层
frame 0 # 切换到堆栈第0层
info frame  # 查看当前层函数信息
info frame 0    # 查看堆栈第0层函数信息
up      # 切换到堆栈上一层
down    # 切换到堆栈下一层

save breakpoints file-name-to-save  # 保存当前断点
source file-name-to-save    # 加载保存的断点
b file-name:line-number if expr==value # 增加条件断点
ignore breakpoint-number count  # 忽略断点count次

watch expr  # 增加观察点
watch expr thread thread-num    # 针对特定线程增加观察点
rw expr # 增加读观察点
aw expr # 增加读写观察点
```

### References
[100-gdb-tips](https://github.com/hellogcc/100-gdb-tips/blob/master/src/index.md)

[Debugging with GDB](https://sourceware.org/gdb/onlinedocs/gdb/)

[GNU](https://www.gnu.org/software/gdb/)

[LLDB](https://lldb.llvm.org/)