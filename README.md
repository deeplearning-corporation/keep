<img width="190" height="185" alt="KEEP Logo" src="https://github.com/user-attachments/assets/c99b2fa5-54b4-405d-9389-d9ba1f8ab919" /> 
<h1>KEEP 编译器</h3>
<h3>C\C++ 编译器</h3>

[![License](https://img.shields.io/badge/License-KEEP-blue.svg)](LICENSE)
[![Downloads](https://img.shields.io/github/downloads/deeplearning-corporation/keep/total.svg)](https://github.com/deeplearning-corporation/keep/releases)
[![BiliBili](https://img.shields.io/badge/BiliBili-KEEP-ff69b4.svg)](https://space.bilibili.com/3493294325631048)

</div>

## 源代码
此 KEEP 编译器为闭源项目，请勿二次分发。
Copyright (c) Deep Learning Corporation. All rights reserved.

## 下载
如果您想下载 KEEP 编译器，可以访问：https://github.com/deeplearning-corporation/keep/release
下载 keep-compiler-release-x64-setup.exe 并运行

## 编译 C 或 C++ 文件

```bash
# 编译C(假如文件名为examples.c)
c.exe examples.c -o program.exe   # 编译后运行 program.exe

# 编译C++
cpp.exe examples.cpp -o program.exe # 编译后运行 program.exe
```

## 示例 C 代码
```c
#include <stdio.h>

int main(){
          printf("Hello World\n");
          return 0;
}
```

编译：（假如文件名为 hello.c）
```bash
c.exe hello.c -o hello-world.exe # 编译完成后运行 hello-world.exe
```

## 贡献
你可以通过我们的 Microsoft 邮件：YS_MFAYGMGRXYG@outlook.com

## 生成的 EXE 文件格式
生成的 EXE 文件格式是 Windows PE（PE 格式 EXE）可执行文件
我们像 MinGW 一样，拒绝输出除 Windows PE 格式的可执行文件。

## 🤝 贡献
虽然 KEEP 是闭源项目，但我们欢迎：

🐛 Bug 报告

💡 功能建议

📖 文档改进

请通过 Issues 提交反馈。

## 感谢
感谢阅读我们的 README 文档。

