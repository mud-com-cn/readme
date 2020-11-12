# readme
突发奇想，用各种语言实现一个有基础功能的mud模板
要有最基本的网络连接，用户管理，登录，房间，移动，容器，指令系统等等
1. https://github.com/mud-com-cn/nodelib  这个是第一个（其实是第二个，我那个lpc的simple mudlib不知道哪儿去了，回头找到传上来），nodejs的实现

2. https://github.com/mud-com-cn/phplib   这个是用php实现的，socket部分用了php自己的socket_select()，做了一点封装，可以换成epoll，然后其他工作基本上就是在翻译nodelib的逻辑实现，目前程度还比较低，大概就是有用户管理，能输入指令（只能响应一个look），有房间，还不能走路。。。。
目标还是实现到差不多nodelib的程度就收手

3. to be continued....


