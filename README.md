#微信公众号开发系列之发送红包-java版本


**1、关于total_amout，此处略坑，100 == 1元钱 ，也就是说 这里的 1 相当于1分钱，所以大家做好处理。微信发送红包不少于1元钱。**
	
**2、关于使用中文签名错误，一定要使用utf-8进行md5。**

博文参考：http://blog.csdn.net/cutelittlebo/article/details/53874450