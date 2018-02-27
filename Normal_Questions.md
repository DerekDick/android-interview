# Normal Android Interview Questions
## Fill in the Blanks

## Answer the Following Questions in Detail
**1. What are the access modifiers you know? What does each one do?**

[Oracle documentation](https://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html)

**2. Can an `Enum` type be a subclass of `java.lang.String`?**

  No. All enums implicitly extend java.lang.Enum. Because a class can only extend one parent, the Java language does not support multiple inheritance of state, and therefore an enum cannot extend anything else.

**3. Can an Interface implement another Interface?**

  Yes, an interface can implement another interface (and more than one), but it needs to use `extends`, rather than `implements` keyword. And while you can not remove methods from parent interface, you can add new ones freely to your subinterface.

**4. What is ADB?**

**5. 简述 Activity 的生命周期。**

**6. 简述 Service 的生命周期。**

**7. ANR 是什么？如何避免 ANR？**

**8. 描述 Android 系统架构。**

**9. 描述 Handler 机制？**

**10. `ListView` 有哪些可以优化的地方？**
