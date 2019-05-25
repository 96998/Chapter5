# T*he fifth chapter JavaBean Technology*

##The advantages of Java Bean
```aidl
一次性编写
任意执行
任何地方重用
至于原因吗,咱也不知道,咋也不敢问(JVM,可以参考深入理解Java虚拟机)


```

## The criterion(标准,准则) of Java Bean
一个标准的JavaBean的类所需要遵守的规范

### 1.实现可序列话接口(java,io.Serializable)
### 2.公共的无参构造方法
### 3.类的声明式非final类型的
### 4.为属性声明访问器
```aidl
属性一般设置为私有的,为其书写get和set方法
```

### Simple属性
```aidl
对应的简单的get和set方法
```

### Indexed属性
```aidl
Indexed属性就是索引属性(数组之类的)的get和set方法
```