# C++标准库(第二版)源码-使用CMake组织

- stl
- linux ansi c
- linux system call
- posix c

记忆c api，先记忆头文件

c++头文件
```shell
wdidada@wdidada-E550:/usr/include/c++/9$ ls
algorithm  cinttypes           cstdio        fenv.h            map              scoped_allocator  typeindex
any        ciso646             cstdlib       filesystem        math.h           set               typeinfo
array      climits             cstring       forward_list      memory           shared_mutex      type_traits
atomic     clocale             ctgmath       fstream           memory_resource  sstream           unordered_map
backward   cmath               ctime         functional        mutex            stack             unordered_set
bit        codecvt             cuchar        future            new              stdexcept         utility
bits       complex             cwchar        initializer_list  numeric          stdlib.h          valarray
bitset     complex.h           cwctype       iomanip           optional         streambuf         variant
cassert    condition_variable  cxxabi.h      ios               ostream          string            vector
ccomplex   csetjmp             debug         iosfwd            parallel         string_view       version
cctype     csignal             decimal       iostream          profile          system_error
cerrno     cstdalign           deque         istream           pstl             tgmath.h
cfenv      cstdarg             exception     iterator          queue            thread
cfloat     cstdbool            execution     limits            random           tr1
charconv   cstddef             experimental  list              ratio            tr2
chrono     cstdint             ext           locale            regex            tuple
```

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

inline express
http://www.cplusplus.com/articles/2LywvCM9/

[cpp reference accumulate](https://en.cppreference.com/w/cpp/algorithm/accumulate)

[adjacent_difference C++ 使用](https://blog.csdn.net/zhangxiao93/article/details/75822424)

用来计算容器相邻元素的关系，除了相邻元素之差，或自定义相邻元素操作：


