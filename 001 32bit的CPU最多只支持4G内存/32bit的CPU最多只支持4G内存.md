### 32bit的CPU最多只支持4G内存
![1](https://github.com/ethaninchina/Hardware/blob/master/001%2032bit%E7%9A%84CPU%E6%9C%80%E5%A4%9A%E5%8F%AA%E6%94%AF%E6%8C%814G%E5%86%85%E5%AD%98/img/1.png)
![2](https://github.com/ethaninchina/Hardware/blob/master/001%2032bit%E7%9A%84CPU%E6%9C%80%E5%A4%9A%E5%8F%AA%E6%94%AF%E6%8C%814G%E5%86%85%E5%AD%98/img/2.png)
```shell
1、1byte = 8bit是内存最小的IO单位（一个存储单位是1byte=8bit）
2、cpu通过内存地址来读写内存存储(内存地址相当于索引、门牌号)
3、32bit的cpu，表示一个内存地址占32bit(4byte)
4、综上所述，一个内存地址占32bit(4byte)，一个内存存储单位占8bit（1byte），而一个地址对应一个存储（1byte）
5、2位的二进制，可以表示00 01 10 11这4种值，那么32位的二进制可以表示2的32次方个值，即32bit/4byte的内存可以表示4294967296个地址
6、32bit内存，可以表示4294967296个内存地址，一个内存地址指向一个内存存储，即4294967296个内存存储
7、而一个内存存储占1byte，所以4294967296个内存存储，就会占4294967296byte内存存储大小 = 4Gbyte内存存储大小
```
