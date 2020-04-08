```xml
 <servlet>
    <servlet-name>SpringMVC</servlet-name>
    <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
<!--    设置配置文件路径-->
    <init-param>
      <param-name>contextConfigLocation</param-name>
      <param-value>classpath:SpringMVC-servlet.xml</param-value>
    </init-param>

<!--    
	设置servlet启动时间
      默认是第一次访问时加载
      此标签中可以设置整数：
        1. > 0 启动时加载。 数值越小，优先级越高
        2. < 0 第一次访问时加载
-->
    <load-on-startup>1</load-on-startup>
  </servlet>
```

![image-20200406123519869](https://i.loli.net/2020/04/06/tqmzSwPiTKIG3os.png)