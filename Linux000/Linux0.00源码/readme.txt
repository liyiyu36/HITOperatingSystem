�Ķ����£�

1. head.s�ļ������м��� .code32
2. Makefile�ļ��У�head.o: head.s��������һ��
   gcc -m32 -c head.s
   ����-m32ʹ�ò�����Ŀ���ļ���32λ�ģ�����64λ����������

3. �鿴�����
   gcc -m32 -c -g head.s
   objdump -D head.o

   as86 -l boot.lst boot.s

����ɹ���
 
by Dr. GuoJun LIU
2014-06-05