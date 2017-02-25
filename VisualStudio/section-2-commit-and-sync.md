## 使用VisualStudio进行repository的修改的commit以及同步操作

不像svn管理系统，commit是直接commit到中心服务器之上的，故而svn的commit操作必须要保证客户端和服务器是处于联网状态的。对于git源代码管理而言，则可以先将代码commit到本地的repository之中，然后在push到服务器上面的时候才会需要联网。

|   |          Local           |           Remote          |
|---|--------------------------|---------------------------|
|svn|                          |[local] commit --> [remote]|
|git|[local] commit --> [local]|[local] sync  <--> [remote]|

