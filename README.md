# -由于第一个项目来的像龙卷风，，，所以记录一下。。。。。。。。。。

一开始接触物模型有点不知所措，通过给的物模型模型文档一步步去看里面的代码分别代表了什么，然后根据示例代码去理解物模型的定义，还是有点痛苦的，什么都不会（物模型是json文件写的，但是我
对json什么都不会，好在json不是很难，看了一会就知道是怎么写的了），慢慢的去看示例和俊辰哥写的物模型之后，开始慢慢的和物模型认识，渐渐的熟悉了，，，，想吐槽的都吐槽完了。。。



渐渐的熟悉了物模型之后开始写自己的物模型，理解了产品和设备的关系并用json写了出来，连接方式和属性是一一对应的，这方便了我如果在连接方式书写有误的话在属性这里还有一次查错机会，，，
（写完之后发现连接方式一个都没错，反而是属性错了好几次，，，呜呜呜），根据写好的物模型去自己开发环境上传验证，在这里认识理解产品的概念以及设备的概念和注册，由于没法在开发环境去注册
设备，因此后面的在测试环境这侧设备时有走了很多弯路。



在开发环境中验证以后就去测试环境开始边测试边继续认识，从这里开始，学习到的东西就很多了，首先是apifox，，，这玩意我不难是真不难，可是要写好一个好的api文档很难，，，这里有很多坑，一
会在隔壁写遇到的坑和处理的办法，嗯就这样开始认识postman，然后开始学习postman的用法，根据post链接和填入的参数开始自己测试，这里是模拟前端去查询我上传的接口文档，，更加深刻的认识api
文档的重要性，也是这里让我觉得写好api文档很必要而且很重要。


在大学没有好好学习的我在这里第一步开始补了，在前端测试接口的时候，不会用网页的f12来帮自己查找错误，以至于我到这里完全不知道干什么，也在这里俊辰哥帮我演示了怎么根据f12来查找自己的问题，
network，payload，header，headerURL，appId等，这里也是最痛苦的一天。。。。。。。。。。。。。



接下来开始根据服务器去查找上传的接口数据错误的地方，这里好在前辈写好的log文件快速让我知道是什么原因，这里又是一个坑所以等下去隔壁说，，，修改好这些错误之后再去查看数据，发现没有不显示的
地方了，这就意味着测试环境也差不多ok了。。。。。。。。。。


现在是进入自己测试的阶段，这里开始认识新的软件offset，，，，，这里是因为一些原因（没记住，以后再来填坑）没法去让软件主动报错，所以根据硬件数据来做中间解析，如果故障那个参数是1的话就去
go里面说有故障了，修改好lua脚本之后就去offset里面查看故障消息，，这里是另一个坑了隔壁说，坑踩完调好以后发现故障提示也是没问题的，终于终于结束了第一个项目。。。。



结束了项目之后开始书写提测文档，这里提测文档有模板，直接使用就好了。emmmm先到这里吧，后面继续补充。



*************************************************************************************************************************************************************************











