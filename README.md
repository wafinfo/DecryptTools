## **前言**

为什么会写这一款综合加解密工具，因为在很多比赛如果算**拿下靶标**不仅**需要获取服务器权限还需要登录网站后台**这时候很多系统**要么数据库连接字符串加密，要么登陆用户加密**而这款工具就是为了解决问题。

**加解密功能**：该工具不仅有**解密**还提供**多种加密**方式。

**配置文件信息功能**：为了在**比赛中尽可能节约时间和提供一个后渗透功能。**

**备忘录功能：**是为了**保存用户自己有一些trick点方便查看，同时也保证自己trick不被公开化**。

## 工具展示

- ## **支持22种加解密**

```
万户OA
金蝶EAS
新华三IMC
蓝凌OA
Weblogic
金蝶云星空
致远OA
H3C CAS
宏景ERP
湖南强智
金和jc6
金和C6
华天动力
亿赛通
帆软报表
用友NC
海康威视IVMS 8700
海康威视IP Camera
金盘 OPAC
JBOSS
SpringEnc
Druid
```

- ## **工具加解密**

![image-20240314102549407](README/image-20240314102549407.png)

![image-20240314101957484](README/image-20240314101957484.png)

![image-20240314102628068](README/image-20240314102628068.png)

![image-20240314100601432](README/image-20240314100601432.png)

![image-20240314101802393](README/image-20240314101802393.png)

![image-20240314103701954](README/image-20240314103701954.png)

- ## **备忘录**

保存的内容均在同级目录`config.properties`文件中

![image-20240314103149582](README/image-20240314103149582.png)

![image-20240314103345377](README/image-20240314103345377.png)

## **需解决问题**

**目前整体框架全部已完成，细节部分未完善**。如果有师傅需求添加**新的系统**（最好能提供必较完善的信息）可以**issue**提或者直接联系我。如果**采纳**了师傅们提供的信息，我会在**致谢名单**添加上各位**师傅ID以表感谢**。

## 参考文章

https://www.cnblogs.com/kexianting/p/11689289.html
https://github.com/jas502n/spring-ENC
https://github.com/chrisjd20/hikvision_CVE-2017-7921_auth_bypass_config_decryptor/
https://github.com/Rvn0xsy/PassDecode-jar
https://www.hedysx.com/2807.html
https://github.com/zhutougg/LandrayDES
https://cloud.tencent.com/developer/article/2204689
https://github.com/TideSec/Decrypt_Weblogic_Password
https://github.com/baogod404/HikvisionDecode