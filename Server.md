# Server Memo

## Service

* yum使用remi仓库， yum --enablerepo=remi install php-mbstring
* svnserve -d -r /www/svn

## RabbitMQ

* 安装目录：/usr/lib/rabbitmq/lib/rabbitmq_server-3.3.5/plugins
* 设置队列生存周期 rabbitmqctl set_policy expiry "mqtt-subscription-worker-qos1" '{"expires": 4294967295}' --apply-to queues


## mosquitto
* 编译mo-auth-plugin，安装mysql-devel，注释掉其他方式ldap等，安装hiredis-devel，libmos…-devel