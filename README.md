# NetworkProgramming
notebooks about network programming

- 网络传输层


- TCP/UDP 区别
| TCP | UDP |
| ------ | ---- |
|  面向连接 | 无连接 |
| 提供可靠服务，通过 TCP 连接传送的数据，无差错、不丢失、不重复、且按顺序到达 | 不保证可靠交付，会有丢包可能，不保证数据顺序 |
| 面向字节流，把数据看成一连串无结构的字节流 | 是面向报文的，是数据报模式 |
| 连接是点到点的 | 支持一对一、一对多、多对一、多对多的交互通信 |
| 首部开销 20 字节 | 首部开销 8 字节 |
| 全双工可靠通信 | 不可靠通信 |

| option | desc |
| ------ | ---- |
|  dat   | hints |
| eng | extension|
 

 

 

 

 

 

 

 

 

 
