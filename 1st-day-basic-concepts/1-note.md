# 一、初识C++
C++ 是一种流行的跨平台语言，可用于创建高性能应用程序——操作系统、浏览器、视频游戏、艺术应用程序等。C++ 是从 C 派生的，并且很大程度上基于它。

# 二、程序模板
C++ 程序是命令或语句的集合。 下面是一个简单的程序模板。
```cpp
#include <iostream>
using namespace std;

int main()
{

  return 0;
}
```
每个 C++ 程序的入口点是 main() 函数，无论程序做什么。花括号 { } 表示函数的开始和结束，也可以称为函数体。括号内的信息表示函数在执行时的功能。

# 三、Hello World

```cpp
#include <iostream>
using namespace std;

int main()
{
  cout << "Hello world!";
  cout << " This " << "is " << "awesome!";
  return 0;
}
```

# 四、输出换行
- **endl**
- **\n**

# 五、注释
- 单行注释 ：//
- 多行注释 ： /* */

# 六、变量
所有变量都必须先定义名称和数据类型，然后才能使用。
```cpp
int myVariable = 10; 
```
# 七、输入
```cpp
int num;
cin >> num;
```
# 八、两数之和

```cpp
#include <iostream>
using namespace std;

int main() 
{
    int a, b;
    int sum;
    cout << "Enter a number \n";
    cin >> a;
    cout << "Enter another number \n";
    cin >> b;
    sum = a + b;
    cout << "Sum is: " << sum << endl;

  return 0;
}
```
# 九、auto关键字
auto 关键字允许您自动扣除正在声明的变量的类型。它从变量的值推断变量的数据类型。
```cpp
 auto x = 4; //integer
 auto y = 3.37; //float
 auto z = "hello"; //string
```
使用 auto 关键字声明的任何变量都应在声明时初始化，否则会出错。
# 十、算数运算符
|    Operator    | Symbol | Form  |
| :------------: | :----: | :---: |
|    Addition    |   +    | x + y |
|   Subtration   |   -    | x - y |
| Multiplication |   *    | x * y |
|    Division    |   /    | x / y |
|    Modulus     |   %    | x % y |
