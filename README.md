
# seekbarwithinstruct
关于一个带指示器的seekbar，初次自定义view很多地方不足；

联系方式
邮箱地址： 1320917731@qq.com
QQ： 1320917731
个人能力也有限，希望一起学习一起进步。


演示
![image](https://github.com/Tiannuo/seekbarwithinstruct/blob/master/app/src/main/java/com/tikou/seekbarwithinstruct/showsample.gif)


## 1.用法
Android studio在gradle可以选择添加或者copy源码（Api>15）：


```java
compile 'com.tikou:seekbarwithinstruct:1.0.0'
```

## 2.使用方式参数说明
目前thum高度必须大于progressdrawble 高度
## Attributes
| name | format | description |
| -----|:----:| ----:|
| numbackground    | reference    | 设置指示器背景的资源文件    |
| numTextSize    | dimension    |  设置指示器内部文字的大小   |
| numTextColor    | color    |   设置指示器内部文字的颜色  |
| numScale    | string    |   设置指示器背景资源文件的箭头和整个图片高的的比例如0.2  |
| numType    | enum    |   设置指示器在seekbar的上面还是下面  |
| numTextFormat    | string    |   设置指示器内部文字的后缀格式，默认是%，如20%，输入"元"，就是20元  |


