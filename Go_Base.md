🚀 Go 语言基础语法与工程化开发实战教程

适合有编程经验的开发者快速掌握 Go 核心语法 + 现代工程实践  
版本：Go 1.22+ | 目标：写出可维护、可测试、可部署的生产级 Go 代码

第一部分：Go 基础语法（30 分钟速成）

1. Hello World & 基本结构
   // main.go
   package main

import "fmt"

func main() {
fmt.Println("Hello, Go!")
}

- 包（package）：每个 Go 文件必须属于一个包，可执行程序入口为 main 包
- 导入（import）：标准库无需路径，第三方库用模块路径（如 github.com/gin-gonic/gin）

2. 变量与类型
   // 声明方式
   var name string = "Go"
   age := 15 // := 自动推导类型（仅函数内可用）

// 基础类型
bool, string
int, int8, int16, int32, int64
uint, uintptr
float32, float64
complex64, complex128

// 特殊类型
byte // uint8 别名
rune // int32 别名（表示 Unicode 码点）

3. 控制结构
   // if (无需括号)
   if x := 10; x > 5 {
   fmt.Println(x)
   }

// for (Go 只有 for 循环)
for i := 0; i  复杂，清晰 > 聪明，组合 > 继承

现在，创建你的第一个工程化 Go 项目吧！🚀