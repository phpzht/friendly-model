# model Generator
#### 创建一个带属性注释的model，让这个IDE能够提示这个model的属性

引入：
将此命令在laravel中注册，并自行解决namespace问题。

使用：
整个命令是复制laravel框架本身的model generator，并做修改，保留了原来命令的所有功能。

php artisan friendly-model:generate model_name table_name [-d connection]

以上参数：

model_name：model类型名称，参考php artisan make:model

table_name：表名称

[-d connection]：可选配置，数据库连接配置

[原文](https://github.com/tiube00001/laravel-frendly)