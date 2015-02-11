#如何添加doubango工程
Writed by luckychunxiao email: `luckychunxiao#163.com`
## 1.把iOS-ngn-stack拖入自己工程
## 2.build phases 中 link binary with libraries中添加lib库（添加以下全部）
![doubango_blog_2](images/doubango_b_2.png)
## 3.build settings 中 architectures 修改Valid Architectures 为armv7
![doubango_blog_3](images/doubango_b_3.png)
## 4.build settings 中点击最上面的+号，添加User-Defined如图
![doubango_blog_4_1](images/doubango_b_4_1.png)
![doubango_blog_4_2](images/doubango_b_4_2.png)
## 5.build settings 中找到Search Paths添加

##### Header Search Paths:

![doubango_blog_5](images/doubango_b_5.png)

##### Library Search Paths:

![doubango_blog_5_1](images/doubango_b_5_2.png)

## 6.build settings 中找到Linking在Other Linker Flags添加
![doubango_blog_6](images/doubango_b_6.png)
## 7.把引用到iOSNgnStack.h的.m文件修改为.mm
![doubango_blog_7](images/doubango_b_7.png)



