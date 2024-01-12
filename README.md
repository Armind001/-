基于USART1中断，接收数据，接收1B，enqueue一个Byte。
在中断函数中只接收，在while中进行处理
dequeue一个Byte，处理一个Byte（该功能需要根据协议自行配置）
