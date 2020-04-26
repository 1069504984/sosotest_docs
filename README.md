# sosotest平台介绍  
点击 [使用文档](SUMMARY.md) 查看具体使用帮助

##
点击 [常见问题解答](/image/常见问题解答.pdf) 查看 常见问题解答 感谢群友 武汉金山-斌宇(QQ:957949761) 编写

## 系统架构图
![图片](/image/接口测试平台架构图opensource.png)
sosotest是一个高效的自动化测试平台，能够高效的帮助团队进行自动化测试，主要功能如下：

## 多服务、多环境、多模式支持
可以灵活的配置被测服务，配置测试环境和请求地址。<br>
普通模式、关键字模式和python模式的多模式支持，适合不同能力的测试人员。<br>
可自定义关键字、自定义python函数和类，实现更好的封装。

## 数据业务分离
全局变量、组合文本功能，实现了平台的数据与业务的分离。

## 数据驱动
python模式支持接口级的数据驱动。<br>
任务优先变量，实现了任务级的数据驱动。

## HTTP/DUBBO测试
支持HTTP接口测试。<br>
支持DUBBO接口测试(telnet invoke方式)。

## 可结合CI工具完成CI
提供了jenkins插件。<br>
提供了invoke接口和CI示例<br>
能够跟CI工具结合进行持续集成。

## HTTP MOCK服务
支持录制，可以设置录制详情。<br>
支持tag进行分组，同样的接口可以给不同用户提供不同返回。<br>
支持restful规范的接口<br>
支持python代码自定义流程，动态返回mock响应结果。

## 多种用例导入模式（postman导入、日志导入）
http支持postman导入，日志导入。<br>
dubbo支持日志导入。

## 多种录制方式（Chrome扩展、报文生成、MOCK代理）
http支持多种录制方式。<br>
Chrome扩展，一键点击生成用例。<br>
复制原始请求报文，一键生成接口用例。<br>
设置app的mock代理，直接生成mock数据后，一键转为接口用例。

## 分布式异步执行任务，支持多任务高并发。
任务执行采用了master-slave的分布式方案，能够接入多个slave实现任务执行的高并发。

# 联系我们
交流反馈QQ群：284333313<br>
作者邮箱：wangjilianglong@163.com<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;liyc_self@163.com 
