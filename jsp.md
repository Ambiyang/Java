1. <% %>是java语句翻译在service里边
2. <%! %>是java语句翻译在service外边
3. <%= %> 翻译在service里边，out.print() 如果只是输出字符串直接写就行了没必要用函数，需要输出变量在字符串里时才需要用该方法
4. 直接写字符串会翻译到service的out.write()里
5.  <%@page %> 设置contenttype
6.  ```
    改造html为jsp时，需
    在头部加上page指令
    href需要加项目名字/oa/list.jsp　href="<%=request.getContextPath()%>/list.jsp"
    
    ```
7. EL ${}相当于.getattribute("item") 从小到大范围读取pageContext,request,session,application
8. 
   
