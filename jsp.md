1. <% %>是java语句翻译在service里边
2. <%! %>是java语句翻译在service外边
3. <%= %> 翻译在service里边，out.print() 如果只是输出字符串直接写就行了没必要用函数，需要输出变量在字符串里时才需要用该方法
4. 直接写字符串会翻译到service的out.write()里
5.  <%@page %> 设置contenttype
   
