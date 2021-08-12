
1.使用命令 vjmap -sur pid 来查看survivor区的内存使用情况

2.使用命令 vjmap -old pid 来查看old区的内存使用情况

3.使用命令 vjmap -all pid 来查看整个堆区的内存使用情况

4.使用命令 jmap -histo pid 来对比查看堆区的内存使用情况，可以感受到明显的区别，vjmap在显示上更有针对性且更加直观
