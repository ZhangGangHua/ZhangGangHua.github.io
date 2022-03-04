## 第一步、下载安装包：
输入命令：

> wget http://mirrors.cnnic.cn/apache/maven/maven-3/3.5.4/binaries/apache-maven-3.5.4-bin.tar.gz

## 第二步、解压缩：

> tar -zxvf apache-maven-3.5.4-bin.tar.gz

## 第三步、配置maven：

> vi /etc/profile

在profile文件加上下面几行：
注意地址不要写错！

```java
export MAVEN_HOME=/opt/apache-maven-3.5.4
export PATH=$MAVEN_HOME/bin:$PATH
```

## 第四步、让配置文件生效：

> source /etc/profile


## 第五步、查看：

>mvn -version

出现这个，表示安装完成：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201106113537656.png#pic_center)

