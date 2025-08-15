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
15. bean初始化顺序@dependson来控制
16. aop添加依赖，@Aspect类，同时必须是bean所以需要@component.EnableAspectJAutoProxy需要加，sb会自动帮忙加。前提是能扫描到sba
17. Spring bean的两种创建方式:BeanFactory, ApplicationContext(加载文件时就会创建对象)
18. use-default-filters="false"创建自己的filter，比如按照注解来过滤
19. autowired不需要set方法，根据类型
20. qualifier根据名字
21. resource可以根据类型，也可以根据名字@Resource(name="name"),非spring关键字，是java的
22. 注解配置，1.添加context 2. 开启组件扫描
23. 


