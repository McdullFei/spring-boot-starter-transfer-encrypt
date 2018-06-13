# spring-boot-starter-transfer-encrypt
 > 将之前项目中使用的报文加密方式重构为springboot starter提供出来。http传输报文实现rsa+aes加解密的springboot starter
 
 - 重写httpmessageconvert
 - 使用aes对称加密方式对于传输报文data进行整体加解密
 - 使用rsa对aes 的加密key进行加密
 - ras公私钥动态获取：在客户端每次启动重新获取公私钥
