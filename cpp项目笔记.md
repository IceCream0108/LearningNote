# tinywebserver

1. 结构体初始化使用如下代码`epoll_event ev = {0};`：epoll_event中包含多个字段。但是当使用0对结构体初始化时，会将所有字段设置为0值，保证安全，若不初始化会导致安全问题。

2. write和read调用

3. writev和readv调用

4. 模板函数，使用是不需要指明类型，与模板类不同。


