1. 构造方法注入constructor-arg
2. array,list,set,map-entry,props-prop
3. <null/> 这个是null;<value/>这是空字符串
4. <>等符号需要转移，或者用cdata标签
5. p命名空间是set注入，c是构造注入
6. 简单工厂：抽象类，具体产品，工厂类。静态工厂
7. @confiuration + @bean配置，如果用@component，bean方法会变成普通方法。@bean用于配置类的方法
8. 第三方jar包里的类必须通过@bean配置
9. @Import必须写在类上，类必须是一个bean
10. @SpringBootTest在测试类里写上才能拿到bean，否则要自己创建context来拿
11. 如同一类有多个bean，先找类型，然后找名字，如果找不到名字，@primary，或者@Qualifier，或者required=false
12. Autowired有多个有参构造函数，并且没有无参构造函数时，可以指定默认启动函数
13. sb的配置文件名字时application.properties，该配置文件不需要用propertysource导入以使value来读取
14. springboottest默认会吧springbootapplication当作配置类。用springboottest(class=TestOrder.class)吧test类作为启动类，配合@bean加载
15. 


