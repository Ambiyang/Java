1. ```
   mvnrepository.com
   conf\settings.xml里配置localRepository,mirror
   自定义settings放在localRepository同级路径下

   -src
    -main
     -java
     -resources
    -test

   compile会下载依赖到maven仓库里
   编译完放进target文件夹
   
   <pluginManagement>
     <plugin>
   ```

2. ```
   <pluginManagement>
     <plugin>
   ```
