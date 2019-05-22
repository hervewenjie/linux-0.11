# linux-0.11
这个repo用来分析linux 0.11源码及整个现代多任务操作系统实现原理

1. BOIS加载磁盘第一扇区bootsect.s
2. bootsect.s加载setup程序
3. setup程序加载system模块
4. system模块包含head及main模块，跳转到main函数执行

# 汇编
linux 0.1x使用2种汇编
1. 产生16位代码的as86和ld86
2. GNU as

# 80x86的保护模式及其编程
# # 80x86的保护模式及其编程
