1. CATALINA_HOME, tomcat服务器的根；JAVA_HOME，JDK的根；PATH=JAVA_HOME\bin；CATALINA_HOME\bin,需要编译还需要配置CLASSPATH=CATALINA_HOME/lib/servlet-api.jar+jsp-api.jar
2. 以来坐标里的servlet需要是provided，不需要运行时，否则会报错。
3. jre java运行环境 tomcat服务器必须
4. conf/server.xml Connector标签可以改端口
5. webapps下部署项目，可以是文件夹也可以是war
6. 转发不需要虚拟路径。服务器发出的不需要。浏览器需要。获取虚拟路径用getContextPath
7. 
