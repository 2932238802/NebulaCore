## std::chrono::system_clock:: to_time_t

---

### 函数原型

```C++
static std::time_t to_time_t( const time_point& t ) noexcept;
```

- 传入一个时间 time_point
- now() 可以生成一个时间time_point [now()](./now.md)
- 返回一个time_t类型 [time_t](../../ctime/time_t.md)

