1. CATALINA_HOME, tomcat服务器的根；JAVA_HOME，JDK的根；PATH=JAVA_HOME\bin；CATALINA_HOME\bin,需要编译还需要配置CLASSPATH=CATALINA_HOME/lib/servlet-api.jar+jsp-api.jar
2. 以来坐标里的servlet需要是provided，不需要运行时，否则会报错。
3. jre java运行环境 tomcat服务器必须
4. conf/server.xml Connector标签可以改端口
5. webapps下部署项目，可以是文件夹也可以是war
6. 转发不需要虚拟路径。服务器发出的不需要。浏览器需要。获取虚拟路径用getContextPath
7. ```
   JavaWeb---Maven&MyBatis：https://cyborg2077.github.io/2022/08/11/JavaWeb01/
   JavaWeb---HTML&CSS：https://cyborg2077.github.io/2022/08/13/JavaWeb02/
   JavaWeb---JavaScript：https://cyborg2077.github.io/2022/08/14/JavaWeb03/
   JavaWeb---HTTP&Tomcat&Servlet：https://cyborg2077.github.io/2022/08/16/JavaWeb04/
   JavaWeb---Request&Response：https://cyborg2077.github.io/2022/08/17/JavaWeb05/
   JavaWeb---JSP：https://cyborg2077.github.io/2022/08/18/JavaWeb06/
   JavaWeb---会话技术：https://cyborg2077.github.io/2022/08/20/JavaWeb07/
   JavaWeb---Filter&Listener&AJAX：https://cyborg2077.github.io/2022/08/21/JavaWeb08/
   JavaWeb---Vue&Element：https://cyborg2077.github.io/2022/08/23/JavaWeb09/
   JavaWeb---综合案例：https://cyborg2077.github.io/2022/08/24/JavaWeb10/
   JDBC和MySQL是看的尚硅谷的课，更多文章可以访问我的博客：https://cyborg2077.github.io/
   ```
