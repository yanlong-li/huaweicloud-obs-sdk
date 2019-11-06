华为云对象储存服务SDK
============
>稳定、安全、高效、易用的云存储服务，具备标准Restful API接口，可存储任意数量和形式的非结构化数据，提供99.999999999%的数据可靠性

产品优势 稳定可靠 安全可信 智能高效 友好易用 稳定可靠

通过多级可靠性架构，保障数据持久性高达99.9999999999%（12个9），业务连续性高达99.99%

智能高效
OBS通过智能调度，并结合传输加速、大数据垂直优化，为用户提供高并发、大带宽、稳定低时延的数据访问体验

安全可信
OBS通过可信云认证，支持服务端加密、防盗链、VPC网络隔离、日志审计、细粒度权限控制，保障数据安全可信

友好易用
OBS支持REST API，提供多种语言的SDK，兼容主流的客户端工具，您可以随时随地通过网络上传、下载、管理您的数据


[华为官方维护SDK地址](https://github.com/huaweicloud/huaweicloud-sdk-php-obs)

华为官方SDK仅支持PHP5.6 及PHP7.3以下版本、并且不能很方便的集成到主流框架  -- 2019年1月23日

我会尽量保持和官方同步更新

更新日志
```log
2019年11月6日 v3.1.3.1
本次并有更新什么内容，只是更新了开源许可和版本号 代码未变更
我们会在官方版本后追加一个小版本，以表示高于官方版本进行的修改

资料&demo:
修复问题：
1. 修复连接OBS服务超时时，解析request-id报错导致异常信息被截断的问题；
2019年1月23日
修复不支持PHP7.3及以上版本问题

修复composer指定版本无法传递到composer问题

优化composer扩展包版本指定问题导致的无法集成到主流框架问题
```

