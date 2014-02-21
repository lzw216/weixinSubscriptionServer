##xampp virtual dir

C:\xampp\apache\conf\httpd.conf

Alias /wxss "D:/mystic/weixinSubscriptionServer" 
<Directory "D:/mystic/weixinSubscriptionServer">
	Options Indexes FollowSymLinks Includes ExecCGI
    AllowOverride All 
    Options None  
    Order allow,deny  
    Allow from all  
	Require all granted
</Directory>