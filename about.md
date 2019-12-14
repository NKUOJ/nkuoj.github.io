# 💡 oj


## 常见问题
#### 1、请使用 Chrome 或 Firefox 使用本OJ

#### 2、编程时不要使用#include <bits/stdc++.h> ，该语句包含了所有c++基础库的头文件

#### 3、 Q：为什么代码在我本机可以通过，提交到OJ总是提示答案错误

A：OJ上的题目提供了多组测试用例，你的代码在本机可以通过仅仅是通过了样例数据，可能存在边界条件考虑不周导致更多的测试数据没有通过，所以会返回答案错误。还有一种可能是你的代码没有处理多个测试用例，例如A+B的代码需要while循环处理。

```c
  #include <stdio.h>
    int main() {
      int a,b;
      while(scanf("%d %d",&a, &b) != EOF)
          printf("%d",a+b);
      return 0;
  }
```

#### 4、 Q：为什么Java代码在我本机运行正常，提交到OJ报编译错误

A：因为Java文件名和类名需要保持一致。


#### 5、 Java代码，请确认类的名字是Main，也不要给代码增加任何package信息。

#### 6、Q：为什么我的代码在本机运行正常，提交到OJ总是报运行超时

A：OJ对每个编程题的运行时间都有限制，一般是限制在10秒，OJ后台判题的机器显然不如你的台式机强劲，所以碰到超时请尽量优化你的代码效率。当然也有可能是你代码对某个测试用例死循环了。

#### 7、 Q：运行错误是什么情况

A：运行错误一般都是数组越界非法访问，野指针乱访问，空指针乱访问等情况造成代码奔溃。

#### 8、 当python 报错：/usr/bin/python3: error while loading shared libraries: libm.so.6: failed to map segment from shared object时，极大可能是给python运行的内存限制过小

#### 9、 测试集结尾符应当注意以回车结束，在编辑题目页面，测试用例末尾手动输入回车。

## A+B 问题各语言代码示例

#### `c`

```c
#include "stdio.h"
int main() {
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", a + b);
    return 0;
}
```

#### `c++`

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

#### `java`

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

#### `python2`

```python2
str = raw_input()
str = str.split()
a = int(str[0])
b = int(str[1])
print a + b
```


内核部分采用: [JudgeServer](https://github.com/QingdaoU/JudgeServer) 

## 各语言编译命令

参考：[语言配置](https://github.com/QingdaoU/JudgeServer/blob/master/client/Python/languages.py)

# 👾 NKUOJ开发团队

## 主要成员

| v1 |[Freezind](https://github.com/Freezind)| [Gorgear](https://github.com/cctv1005s) | lbx | | |
| --------- | --------- | --------- | --------- | --------- | --------- |
| **v2** | **lbx** | [**William**](https://github.com/William-YanHua) | **wyh** | **lbq** | [**Gorgear**](https://github.com/cctv1005s) |



