<picture>
  <source media="(prefers-color-scheme: dark)" srcset="Neon-plus-logo.svg">
  <img src="Neon-plus-logo.svg" alt="NeonLang-Logo" height="128">
</picture>

# NeonPlus 1.0

NeonPlus 是一个基于C/C++编程语言的编程语言，一种无限VM编译器/VM虚拟机可以调用C-API、字节码转译C源码

Main.np
```java
public class Main {
    public static void main(String[] args) {
        int rt = 67;
        std.printf("Hello World!");
        string fercn = "rt:" + rt;
        std.printf("print: {fercn}", fercn);
        System.out.println(print: " + fercn);
        retuen 0;
    }
}

```





```
plug "stdio";
type main () {
  var e = 1;
  var makr = "Haex"
  printf("Hello World!");
  // console.writeln("Hello World!");
}
```
```
#include <stdio.h>
int main ()
{
  printf("Hello World!");
  return 0;
}
```

```
// Neon compiler
Neon
  File
  Lexer
  Parser
  ASTNode
  

```

| 系统 | 名字 | 支持 | 
|:--:|:--:|:--:|
| Wnodws | NeonPlus | ✅ |
| linux | ? | ✅ |
| NoteOS | ? | ✅ |
| Mac | ? | ✅ |

