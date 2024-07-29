tgState
==

# 参数说明

必填参数

 - target
 - token

可选参数

 - pass
 - mode
 - url
 - port

## target

目标可为频道、群组、个人

当目标为频道时，需要将Bot拉入频道作为管理员，公开频道并自定义频道Link，target值填写Link，如@xxxx

当目标为群组时，需要将Bot拉入群组，公开群组并自定义群组Link，target值填写Link，如@xxxx

当目标为个人时，则为telegram id(@getmyid_bot获取)

## token

填写你的bot token

## pass

填写访问密码，如不需要，直接填写```none```即可

## mode

 - ```p``` 代表网盘模式运行，不限制上传后缀
 - ```m``` 在p模式的基础上关闭网页上传，可私聊进行上传（如果target是个人，则只支持指定用户进行私聊上传

## url

bot获取FileID的前置域名地址自动补充及api返回完整url的补充

## port

自定义运行端口

# 管理

## 获取FIleID

对bot聊天中的文件引用并回复```get```可以获取FileID，搭建地址+获取的path即可访问资源

如果配置了url参数，会直接返回完整的地址

![image](https://github.com/csznet/tgState/assets/127601663/5b1fd6c0-652c-41de-bb63-e2f20b257022)
