这是什么？

这是一个基于mohist/banner项目的分支

1.20.1fabric-0.15.11

物理cpu小于8核无法正常运行

以兼容地毯及其扩展，并优化生电服务器的体验

我们实现了地毯 fabric+bukkit/spigot的server

 对fabric-mod兼容性                                 

      poor          完全不兼容锂，servercore，create,中世纪武器                                      

对paper/bukkit/spigot兼容性     

      better

   不可以更新已有mod，plugin和serverloader，已经和原文件不同，会导致server的异常

sculk做到了什么？

高效率的内存策略，非均匀性的内存调度，GC高并发和高频率的内存回收使得该服务端可以以最小594MB的RAM启动

线程的异步性，有非常好的区块生成和玩家交互，非常适用于多核的服务器

  精简的运行库，可以极大的减少冗余占用
