## std::time

---
### 函数模型

```C++
char* ctime(const std::time_t* time);
```

- 参数
  - time 要打印的时间

- 作用
  - 转换给定的从纪元起时间为日历本地时间，再转换为文本表示
