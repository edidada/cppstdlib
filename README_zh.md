# C++标准库(第二版)源码-使用CMake组织

[C++标准库（第2版）豆瓣链接](https://book.douban.com/subject/26419721/)

`gcc -lrt test.c -o`

测试

`gcc test.c -o test -lrt`

cmake如何添加

[cmake 添加头文件目录，链接动态、静态库](https://www.cnblogs.com/binbinjx/p/5626916.html)

### note

不知道dl和rt表示什么意思，网上搜索了半天，就查找dl表示动态链接库，rt表示real time，生成程序是需要libnet.so,libdatabase.so等，但是target_link_libraries都没写出来，我就想问下dl是不是就是表示链接link_directories里面所有的.so动态链接库文件，那rt又是代表什么具体含义
dl是libdl.so,rt是librt.so的缩写，其实是静态加载了这两个动态链接库


### head file
.hpp格式的头文件

### vector

vector
- insert
- end

```c++
template <typename T>
inline
```

inline
http://www.cplusplus.com/articles/2LywvCM9/

[cpp reference accumulate](https://en.cppreference.com/w/cpp/algorithm/accumulate)

[adjacent_difference C++ 使用](https://blog.csdn.net/zhangxiao93/article/details/75822424)
