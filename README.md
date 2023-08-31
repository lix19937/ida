# ida   

.a/.so --> .c       

## 反汇编    
机器可执行代码 -->  汇编语言源代码     

objdump  

objdump -l -C -S a.out    
objdump -j .text -l -C -S a.out   

```
-d:将代码段反汇编
-S:将代码段反汇编的同时，将反汇编代码和源代码交替显示，编译时需要给出-g，即需要调试信息。
-C:将C++符号名逆向解析。
-l:反汇编代码中插入源代码的文件名和行号。
-j section:仅反汇编指定的section。可以有多个-j参数来选择多个section。
```      
