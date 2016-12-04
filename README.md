# Zan IntelliJ Plugin - Alpha

`PHPStorm 2016.1.2` `PHPStorm 2016.2.1`

`IntelliJ IDEA 2016.1` `IntelliJ IDEA 2016.2`

测试通过

## Install

Preference -> Plugins -> Install plugins from disk... -> 选择ZanPlugin.jar -> restart PhpStorm

## Feature

### 1. Db::execute("sid参数自动补全");
![sid自动补全](https://cdn.rawgit.com/goghcrow/ZanPlugin/master/screenshot/completation_db_execute.gif)

### 2. Db::execute("sid ctrl+mouse 自动跳转到sql文件定义位置")
![sql跳转](https://cdn.rawgit.com/goghcrow/ZanPlugin/master/screenshot/reference_sqlmap.gif)

### 3. Client::call("参数自动补全");
![clientcall自动补全](https://cdn.rawgit.com/goghcrow/ZanPlugin/master/screenshot/completation_client_call.gif)

### 4. [Iron] Client::call("内部调用 ctrl+click 跳转到api定以方法");<br>

支持以下三种形式：

1. Client::call("")
2. Api_Client::call("")
3. $this->call("")

![iron-clientcall内部调用跳转](https://cdn.rawgit.com/goghcrow/ZanPlugin/master/screenshot/iron_client_call_reference.gif)

## TODO

1. sqlmap文件名与table字段不一致情况
2. 检查sid对应sql文件与项是否存在
3. 检测client::call配置是否存在
4. resource/sql 文件夹内sqlmap文件反向查找使用者