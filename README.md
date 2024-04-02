将该脚本添加入 KEIL 的 After Build/Rebuild 栏中可实现自动将所需文件如 hex/bin 集中输出到指定目录中，同时为其添加版本号与时间等信息。

目前支持的功能：
- 识别版本号并添加到输出文件名中

输出的文件
- BIN 文件
- HEX 文件（需要勾选 KEIL 的 Create HEX file 选项）
- 反汇编文件
