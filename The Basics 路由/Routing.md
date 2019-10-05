
# 路由

-   [基本路由](https://laravel.com/docs/5.8/routing#basic-routing)
    -   [重定向路由](https://laravel.com/docs/5.8/routing#redirect-routes)
    -   [视图路由](https://laravel.com/docs/5.8/routing#view-routes)
-   [路线参数](https://laravel.com/docs/5.8/routing#route-parameters)
    -   [必需参数](https://laravel.com/docs/5.8/routing#required-parameters)
    -   [可选参数](https://laravel.com/docs/5.8/routing#parameters-optional-parameters)
    -   [正则表达式约束](https://laravel.com/docs/5.8/routing#parameters-regular-expression-constraints)
-   [命名路由](https://laravel.com/docs/5.8/routing#named-routes)
-   [路由组](https://laravel.com/docs/5.8/routing#route-groups)
    -   [中间件](https://laravel.com/docs/5.8/routing#route-group-middleware)
    -   [命名空间](https://laravel.com/docs/5.8/routing#route-group-namespaces)
    -   [子域路由](https://laravel.com/docs/5.8/routing#route-group-sub-domain-routing)
    -   [路由前缀](https://laravel.com/docs/5.8/routing#route-group-prefixes)
    -   [路由名称前缀](https://laravel.com/docs/5.8/routing#route-group-name-prefixes)
-   [路线模型绑定](https://laravel.com/docs/5.8/routing#route-model-binding)
    -   [隐式绑定](https://laravel.com/docs/5.8/routing#implicit-binding)
    -   [显式绑定](https://laravel.com/docs/5.8/routing#explicit-binding)
-   [回退路由](https://laravel.com/docs/5.8/routing#fallback-routes)
-   [频率限制](https://laravel.com/docs/5.8/routing#rate-limiting)
-   [表单方法伪造](https://laravel.com/docs/5.8/routing#form-method-spoofing)
-   [访问当前路由](https://laravel.com/docs/5.8/routing#accessing-the-current-route)

## [基本路由](https://laravel.com/docs/5.8/routing#basic-routing)
  
构建基本的路由只需要一个 URI 与一个  `闭包`  ，这里提供了一个非常简单优雅定义路由的方法：

```php
Route::get('foo', function () {
    return 'Hello World';
});
```

