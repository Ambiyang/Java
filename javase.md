1. 使用外部类的 this 引用访问 外部类名.this.成员名
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
6. 
