# rust_mongo_decimal128_tostring
mongodb里面的浮点数使用的是`decimal128`类型，在rust-mongodb的包里面，`to_string`方法只能获取到一个`int array`。而且没有其他的操作方式
这个包可以将那个`int array`转换为一个浮点数字符。
拉取到本地后可以用`cargo run test`看项目中的测试案例的情况。
