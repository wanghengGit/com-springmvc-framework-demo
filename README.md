# com-springmvc-framework-demo
源码主要用于学习SpringMVC机制原理，根据SpringMVC原理自实现一个简单的前端控制器DispatcherServlet，完成API请求并返回处理结果。内容主要包括：自定义@Autowried,@Controller,@RequestMapping,@ResponseBody,@Service注解，以及实现SpringMVC项目启动时初始化过程中的行为： 1. 扫描配置路径下带有注解的类. 2. 初始化所有的类，放入到IOC容器中，实现@Autowried自动注入. 3. 初始化HandlerMapping，根据url映射不同的Controller方法. 4. 拦截URL请求，执行相应的方法. 5. 返回Handler处理结果.
