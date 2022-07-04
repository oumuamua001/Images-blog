### 名词解释

@PostMapping：是@RequestMapping(value = "…", method = RequestMethod.POST)的简写，只支持 Post 请求，主要用于新建数据（提交数据）

@PutMapping：是 @RequestMapping(value = "…", method = RequestMethod.PUT) 的简写，只支持 Put 请求，通常用于修改数据

@DeleteMapping：是 @RequestMapping(value = "…", method = RequestMethod.DELETE) 的简写，只支持 Delete请求，通常用于删除数据

@ResponseBody：用于注解 Controller 方法，将方法返回的对象转换为指定格式后（常为 JSON 格式），写入到Response 对象的 body 数据区。

@PathVariable ：将 URL 中占位符参数绑定到控制器处理方法的入参中

Lombok 注解：@Data：提供类所有属性的 getter/setter 方法，此外还提供了 equals、hashCode、toString 方法。@NoArgsConstructor ：为类提供一个无参的构造函数。@AllArgsConstructor ：为类提供一个全参的构造函数

Swagger3 注解：@Tag()：Controller 类上，用于描述接口信息。@Operation()：Controller 方法上，用于描述接口方法信息。@Schema()：模型类(DTO)或属性上，用于描述类或属性信息

swagger：swagger 是一个规范且完整的框架，用于生成、描述、调用和可视化 RESTful 风格的 Web服务，swagger 优势主要在于支持 API 自动生成同步在线文档以及 API 在线测试功能。

Shiro 框架三个核心概念：Subject：当前用户  SecurityManager：是 Shiro 的核心，管理所有用户的安全操作  Realm：是 Shiro 连接数据的桥梁

Shiro 的 Realm：Realm 是 Shiro 的安全数据源，要验证用户身份，Shiro 需要从 Realm 获取相应的用户进行比较以确定用户身份是否合法；也需要从 Realm 得到用户相应的角色/权限进行验证用户是否能进行操作。

Vue 相关指令：v-show 和 v-if 区别：v-show 的功能是根据条件决定是否展示元素(false 时隐藏元素)。v-if 的功能是根据条件决定是否渲染元素(false 时不创建元素)。

Axios：Axios 是一个基于 promise 的网络请求库，作用于 node.js 和浏览器中。在服务端它使用原生 node.js http 模块, 而在客户端(浏览端)则使用 XMLHttpRequest。