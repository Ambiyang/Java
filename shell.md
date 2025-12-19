1. `运算式 $(()),$[],expr`
2. basename 文件名 dirname 除了文件名以外的路径名
3. `$*所有参数当成一个整体，只拿到一个参数 $@ 拿到多个参数`
4. `$0函数名`
5. `/etc/profile`定义环境变量，修改完后必须执行source /etc/profile使之生效
6. $() = ``可以执行cmd
7. ubantu 管理权限每次都要sudu 可以用sudo passwd设定密码后切换到root，su root就好了，提示符会从$变成#
8. 多行注释`:<<!!`
9.  grep -v 不包含
10.  `/etc/rsyslog.conf`定义log事项
11.  
```
(l..e).*\1
匹配 like my like
不匹配 like my love
```
12. sed 先用-n取消默认输出 再用p打印
13. 过滤 sed "/game/d" 1.txt -i 选出含有game的行删除，-i表示对源文件操作，不然只是在打印中删除
14. 1,10 1到10行 2,$ 2到结尾 2,+3 第二行开始数3行
15. 替换 s/src/des/g
16. 2a 第二行后添加
17. 

