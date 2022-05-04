# Code05第六个项目——登陆界面

# 实验目的

- 掌握布局的组合使用方式；
- 掌握Vector Asset资源的使用方式；
- 掌握Image View、View等控件的使用方式；

# 实验要求

- 创建布局文件并对根据要求对布局进行设置；

# 实验总结

1.Intent的使用:显式Intent,Intent的构造函数Intent(Context packageContext, Class<?> cls)
，第一个参数Context要求提供一个启动活动的上下文，第二个参数Class则是指定想要启动的目标活动。

``` java
Intent intent=new Intent(LoginActivity.this,NaviActivity.class);
startActivity(intent);
```

# 参考

https://www.cnblogs.com/wanderingzj/p/4928460.html

https://xxgqin.gitbook.io/android/ch02/ch02-3