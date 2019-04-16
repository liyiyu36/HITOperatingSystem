改动如下：

1. head.s文件里首行加上 .code32
2. Makefile文件中，head.o: head.s下面增加一行
   gcc -m32 -c head.s
   参数-m32使得产生的目标文件是32位的，否则64位机编译会出错

3. 查看反汇编
   gcc -m32 -c -g head.s
   objdump -D head.o

   as86 -l boot.lst boot.s

编译成功！
 
by Dr. GuoJun LIU
2014-06-05