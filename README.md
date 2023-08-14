# folder-infoFinder
## ！！！声明！！！

**本程序仅供于学习交流，请使用者遵守《中华人民共和国网络安全法》，勿将此工具用于非授权的测试，开发者不负任何连带法律责任。**



## 介绍

wx小程序自动反编译、敏感信息扫描、结合扫描信息自动进行未授权fuzzing测试。



## 用法

```
python main.py -h
```

相关配置修改 config.yaml文件即可。



## 注意事项

**本程序仅供于学习交流，请使用者遵守《中华人民共和国网络安全法》，勿将此工具用于非授权的测试，开发者不负任何连带法律责任。**

**由于未授权fuzzing测试具有很大的危险，本程序默认关闭使用该功能，如果要求用请自行更给config.yaml中的配置信息。**



## 后续

- 加入基本的漏洞扫描：spring、tomcat、swagger类的。
- 加入 ai 识别能力，对fuzzing的payload进行优化，剔除相关危险操作的URI、自动补充相关参数。
- API封装。
