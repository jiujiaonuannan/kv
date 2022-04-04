# kv server

1. 最核心的功能是根据不同的命令进行诸如数据存贮、读取、监听等操作；
2. 而客户端要能通过网络访问 KV server，发送包含命令的请求，得到结果；
3. 数据要能根据需要，存储在内存中或者持久化到磁盘上。

# How to run this server

1. 在一个终端上输入下面的命令： RUST_LOG=info cargo run --example server --quiet
2. 另外启动一个终端执行：RUST_LOG=info cargo run --example client --quiet
