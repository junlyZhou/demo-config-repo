# demo-config-repo
学习springcloud中config模块的动态配置;

配合springclouddemo工程使用的动态配置文件库！

动态配置文件的名称命名有一定的规范，必须是以模块名称开头，后面添加-dev 或则 -test  等等；如服务名称为： product-server  那么定义开发环境配置文件命名为  :   product-server-dev.yml   定义测试环境名称如 : product-server-test  等等！！

修改配置之后必须访问下面网址刷新配置（刷新后配置才能生效）/actuator/bus-refresh：
http://127.0.0.1:8085/actuator/bus-refresh
