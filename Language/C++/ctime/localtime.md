## std::localtime

---

### 函数原型

```Cpp
std::tm*localtime (const  std::time_t*  time);
```
 
---

### 主要功能

- 转换作为std::time_t值的从纪元起时间到以本地时间表达的日历时。

---

### 用法

```c++
#include <time.h>
time_t tmNow = time(NULL);
tm *ptmNow = localtime(&tmNow);  //从tm结构体中可以取到年月日时分秒等值。
```
