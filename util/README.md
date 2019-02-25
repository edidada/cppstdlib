# cppstdlib

## util

- chrono1
- chrono2
- clock1
- enableshared1
- sharedptr1
- timepoint1
- uniqueptr1
- weakptr2

### chrono1


```shell

chrono1
epoch: Thu Jan  1 08:00:00 1970
now:   Sun Feb 24 22:44:04 2019
min:   Tue Sep 21 08:18:27 1677
max:   Sat Apr 12 07:47:16 2262

```

### chrono2

```shell

chrono2
epoch:     Thu Jan  1 08:00:00 1970
later:     Sat Jan  3 07:55:00 1970
diff:      2875 minute(s)
diff:      1 day(s)
-1 year:   Fri Jan  3 07:55:00 1969
-50 years: Thu Jan 16 07:55:00 1919
-50 years: Wed Jan 27 08:00:43 1869

```

### clock1

```shell

clock1
system_clock: 
- precision: 0.000001 milliseconds
- is_steady: false

high_resolution_clock: 
- precision: 0.000001 milliseconds
- is_steady: false

steady_clock: 
- precision: 0.000001 milliseconds
- is_steady: true

```

### enableshared1

```shell

enableshared1
nico's family exists
- nico is shared 1 times
- name of 1st kid of nico's mom: nico
delete nico
delete nico's dad
delete nico's mom
jim's family exists
delete jim
delete jim's dad
delete jim's mom

```

### limits1

```shell

limits1
max(short): 32767
max(int):   2147483647
max(long):  9223372036854775807

max(float):       3.40282e+38
max(double):      1.79769e+308
max(long double): 1.18973e+4932

is_signed(char): true

is_specialized(string): false

```

### minmax1

```shell



```

### pair1

```shell

pair1
Foo::Foo(tuple)
Foo::Foo(args...)

```

### ratio1


```shell

ratio1
5/3
5/3
1/1
0/1
-7/3

```

### sharedptr1

```shell

sharedptr1
Jutta  Jutta  Nico  Jutta  Nico  
Jutta  Jutta  Nicolai  Jutta  Nicolai  
use_count: 4

```

### sharedptr2
此项目的作用是： 删除`tmpfile.txt`文件

### sharedptr3

```shell

util/sharedptr3.cpp:34：对‘shm_open’未定义的引用
util/sharedptr3.cpp.o：在函数‘SharedMemoryDetacher::operator()(int*)’中：
util/sharedptr3.cpp:25：对‘shm_unlink’未定义的引用

```

### timepoint1

```shell

timepoint1
Fri Jan  1 00:00:00 2010
Mon May 23 13:44:00 2011

```

### tuple1

```shell

tuple1
41 6.3 nico

```

### tuple2

```shell

tuple2
io: [77,1.1,more light]

```

### uniqueptr1

```shell

uniqueptr1
process util_timepoint1
process util_pair1
process cmake_install.cmake
process util_ratio1
process util_tuple2
process Makefile
process CMakeCache.txt
process util_tuple1
process util_sharedptr2
process cppstdlib
process .
process util_enableshared1
process util_limits1
process util_sharedptr1
process util_uniqueptr1
process cppstdlib.cbp
process ..
process util_chrono2
process CMakeFiles
process util_minmax1
process util_sharedptr3
process util_clock1

```

### weakptr1


```shell

weakptr1
nico's family exists
- nico is shared 3 times
- name of 1st kid of nico's mom: nico
jim's family exists

```

### weakptr2

```shell

weakptr2
nico's family exists
- nico is shared 1 times
- name of 1st kid of nico's mom: nico
delete nico
delete nico's dad
delete nico's mom
jim's family exists
delete jim
delete jim's dad
delete jim's mom

```
