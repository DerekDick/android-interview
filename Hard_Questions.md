# Hard Android Interview Questions
## Fill in the Blanks
**1. The method \_\_\_\_ is called only once in the life cycle of a `Fragment`.**

  `onAttached()`

**2. List some typical methods of HTTP request/responses: \_\_\_\_.**

**3. Android 中为了捕获未捕获的异常，需要实现的接口是 \_\_\_\_。**

  `Thread.UncaughtExceptionHandler`

**4. Android 中获取应用内存限制的方法是 \_\_\_\_。**

  `ActivityManager.getMemoryClass()`

## Answer the Following Questions in Detail
**1. Can a static method be overridden in Java?**

  While child class can override a static method with another static method with the same signature (return type can be downcasted), it is not truly overridden - it becomes "hidden", but both methods can still be accessed under right circumstances (see question about overloading/overriding above).

**2. 简述 View 的绘制过程。**

**3. 如何将已有的 MySQL 的数据备份文件(\*.db)导入到 Android 的数据库中？**

**4. 简述 MVP 和 MVVM 架构及二者的优缺点。**

**5. 什么是 OOM？那些情况下常常出现 OOM？如何避免这些情况的发生？**

**6. 简述 SurfaceView 和 View 的区别。**
