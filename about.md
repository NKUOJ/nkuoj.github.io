# oj

内核部分采用: [JudgeServer](https://github.com/QingdaoU/JudgeServer) 

## 应用示例

**a + b 问题: 输入两个数字，输出两个数字的和**

**输入示例**：

```shell
1 2
4 5
10 21
```

**示例输出**:

```shell
3
9
31
```

**各语言代码示例**

*c*

```c
#include 'stdio.h'
using namespace std;
int main() {
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", a + b);
    return 0;
}
```

*c++*

```c++
#include <iostream>
using namespace std;
int main() {
    int a, b;
    cin >> a >> b;
    cout << a + b << endl;
    return 0;
}
```

*java*

```java
import java.util.Scanner;
public class Main {
    public static void main(String [] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println(a + b);
    }
}
```

*python 2*

```python2
a = input()
b = input()
print a + b
```

## 各语言编译命令

```shell
# c | c++
gcc -o ./main.c
gcc -o ./main.cpp
# java
javac ./main.java
# python 无需编译，直接运行
python main.py
```



# NKUOJ开发团队

## 主要成员

### v1

- [Freezind](https://github.com/Freezind)
- [Gorgear](https://github.com/cctv1005s)
- 李博学

### v2

- 李博学
- 严骅
- 王宇博
- 赖柏琦
- [Gorgear](https://github.com/cctv1005s)

