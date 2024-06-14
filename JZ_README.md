<div align="center">
<h1 align="center">JZ-Chatgpt-on-wechat</h1>
基于Chatgpt-on-wechat的本地修改版本。
</div>

## 版本说明
沿用源仓库的版本号，增加最后的日期域。

目前的模型采用oneapi提供的服务接口，支持：
- jack/llama3-8b-chinese:latest
- qwen:14b
- qwen:7b

### 运行
- 后台启动：nohup python3 app.py & tail -f nohup.out 
- 退出：ps -ef | grep app.py | grep -v grep，然后 kill -9 xxxx

## 升级事项
- timetask插件的文件迁移：plugins/timetask/taskFile/timeTask.xlsx

## 更新日志

>**[24/6/14]：** [1.6.6.240614]同步更新源仓库，更新代码。

>**[24/6/2]：** 更新了插件 Apilot，修复部分BUG。

>**[24/6/1]：** [1.6.5.240601]同步更新源仓库，更新代码。

>**[24/5/14]：** [1.6.0.240514]添加定时任务插件 timetask。

>**[24/5/13]：** [1.6.0.240513]同步源仓库，更新代码，保留相关配置文件。

>**[24/3/7]：** [1.5.7.1.240307]同步源仓库，初始化代码。初始化config.json文件。


