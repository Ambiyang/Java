1. ```
   mvnrepository.com
   conf\settings.xml里配置localRepository,mirror
   自定义settings放在localRepository同级路径下

   -src
    -main
     -java
     -resources
     -webapp
    -test

   compile会下载依赖到maven仓库里
   编译完放进target文件夹
   
   <pluginManagement>
     <plugin>

   生命周期
   build-plugins-plugin-executions-execution-(goals-goal|phase)
   ```

2. ```
   可选依赖，父包看不到子包的依赖
   <dependency>
    <optional>
   也可以在父设定里主动排除
   <dependencies>
      <dependency>
        <exclusions>
         <exclusion>
   scope：1主程序，2测试，3包
   compile 123(log4j) test 2(junit) provides 12(servlet-api) runtime 3(jdbc)
   ```

3. ```
   pom里packaging指定pom
   聚合
   modules-module这里写的是相对路径
   
   继承 用于指定版本
   parent

   ```
