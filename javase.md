1. 内部类使用外部类的变量 this 引用访问 外部类名.this.成员名 外部类名.this就是实例调用者
2. 数据类型，char=1000 超过范围会报错，byte|short和char不能互相赋值
3. ```
   byte b2 = 1;
   short s1 = 1;
   short s2 = b2 + s1;报错，因为byte|short|char运算时会自动转换成int运算后得到int，但是int不能付给short
   
   基本类型和字符串可以相互转换
   基本类型 + "" = 字符串
   Integer.parseInt(字符串)
   
   字符串 + 字符串 = 字符串
   字符 + 字符 = int
   ```

4. 子类构造器会自动调用父类的无参构造器
5. 如果父类声明了带参构造器的话，父类的无参构造器就不会自动生成
6. 静态代码块只会执行一次，代码块每次生成类的实例都会执行1次。
7. 执行顺序：静态变量/静态代码块 > 变量/代码块 > 构造器
8. 父静，子静，父普，父构，子普，子构
9. JDK8以后，IF可以写3中方法，抽象，默认，静态
10. 接口里的变量都是public static final的
11. 局部类不能定义修饰符，本来就是局部变量，作用域仅限于方法体或者代码块内
12. 匿名内部类new IF是生成一个新类及其实例，new类相当于继承该类并生成其实例
13. java要求有可能抛出异常的程序必须处理，否则编译报错。运行异常可以不处理（有默认处理），否则要么try catch要么throw
14. ```
    String a = "abc"   指向常量池
    String b = new String("abc") 指向堆
    a.equals(b) T
    a == b F
    a == b.intern() T intern返回常量池里的字符串地址，没有则添加到常量池里
    String a = "hello" + "world" 指向常量池
    b = "hello" 
    c = "world" 
    String a = b + c a指向的不是常量池，而是堆，底层是stringbuilder操作hello world，返回了堆中的变量地址
    ```
15. 参数传递字符串和数组，字符串无法修改，数组却可以修改元素。本质是看修改了谁的内存。其实就是引用型数据很难通过参数传递的形式来修改其内容。
16. 不能把字符串当成数组，如str[0],需要用charat
17. arraylist和linkedlist都是线程不安全的
18. 
