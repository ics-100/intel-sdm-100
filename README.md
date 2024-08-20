### Intel® 64 and IA-32 Architectures Software Developer Manuals


## 术语
* `m`: `memory` 内存


**寄存器**

* `r`: `register` 寄存器
* `Sreg`: `segment register` 段寄存器
* `rb`: `Register byte` (字节8位)
* `rw`: `Register Word`
* `rd`: `Register Dword`:


**立即数**

* `imm`: `immediate` 立即数
* `ib`: `Immediate Byte` 字节立即数(8位)
* `iw`: `Immediate Word`: 双字节立即数(16位)
* `Id`: `Immediate Dword` 四字节立即数(32位)


```
88 /r		MOV r/m8, r8				mov r8 to r/m8
; /r (r)是指纯寄存器操作数
; /r (/) 是指要将这个寄存器的编号添加到ModR/M的中间部分
```

```
C7 /0 iw	MOV r/m16, imm16
; /0 reg部分添加000
```


## Path

> <https://www.intel.com/content/www/us/en/developer/technical-library/programming-guides.html>

* `Product` / `Processors`
* `Intel® 64 and IA-32 Architectures Software Developer's Manual Volume`



## Ref

* <https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html>
* [你管这破玩意叫操作系统源码 | 第一回 最开始的两行代码](https://mp.weixin.qq.com/s/LIsqRX51W7d_yw-HN-s2DA)
* [X86汇编语言：实模式到保护模式 - 章节23:指令的格式及其操作尺寸](https://study.163.com/course/introduction/1209670804.htm)