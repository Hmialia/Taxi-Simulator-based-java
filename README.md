# Taxi-Simulator-based-java
出租车模拟器

本程序通过模拟一辆出租车运营情况，计算出每天的结余。
亮点：
可以预设客流量高峰时间，通过余弦函数模拟高峰时间附近上车人的概率。
每一站都可以显示出租车行走的方向，到达的时间，载客人数，下车人数，收款金额，下车人数，如果到达设有加油站的站点也可以显示加油量，加油金额。

预设条件：
有一辆出租车，初始金额1000元，初始油量100升。每天7点前开始工作，21点后就下班。

出租车在一条直线线路上不断往返行驶，先路上从西到东有1到10个站，其中3站和8站有加油站。

每行驶一站路消耗3升油量，如果油量低于20升且经过加油站司机会花钱加油到满。每升油3元钱。如果钱不够司机会放弃工作，游戏结束。

当出租车经过每个站时，有可能会有乘客下车也有可能会有上车。如果车上的空位不够，那么同一站准备上车的人都不会上车（他们想一起乘车）。下车时每个人根据自己的需要下车（不再结伴），下车时每人给司机交16元车费。

有早，中，晚三个人流高峰时间，在相应时间附近上车人会明显变多。

程序操作：
程序运行时，先显示初始金额和油量，然后按到达每站的时间一次显示第一天内出租车的运营情况，每天结束工作后，会再显示剩余金额和油量，此时可以根据提示按相应按键，选择开始下一天或结束模拟。

程序实现：
本程序由3个类实现： 分别是Taxi.java Time.java RunBusiness.ava
