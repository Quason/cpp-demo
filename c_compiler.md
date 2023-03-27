# --- 一些主流的C/C++编译器
GCC (目前看来几乎是唯一选择)
Microsoft Visual C++
LLVM Clang
Intel C++ compiler
TCC
Borland C++

# --- Windows平台使用GCC
MinGW: Minimalist GNU for Windows
Cygwin: Cygnus Windows

# --- MacOS平台c语言编译器
clang是mac自带的c/c++编译器，和gcc非常相似，但是为了完全一致和迁移考虑，还是建议安装GNU官方的gcc
``` bash
brew install gcc
cat >> ~/.bash_profile << EOF
alias gcc='gcc-11'
alias cc='gcc-11'
alias g++='g++-11'
alias c++='c++-11' 
EOF
```

# --- VSCode使用gcc进行编译
