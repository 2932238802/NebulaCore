## decltype 用法

---

### 示例用法

```C++
#include<iostream>
template<classT,classK>
auto  Sum(T  x,K  y)  ->  decltype(x+y)
{
    return  x  +  y;
}
int  main()
{
    std::cout<<Sum(1,3)<<std::endl;
    std::cout<<Sum(1.3,32)<<std::endl;
    std::cout<<Sum(1.1111,34)<<std::endl;
    return 0;
}
```
