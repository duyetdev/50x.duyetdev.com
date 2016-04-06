# 50x.duyetdev.com
Static 50x error page.

# Setup 
### Nginx

Edit nginx config `/etc/nginx/sites-enabled/default`
```
error_page 500 502 503 504 =301 https://50x.duyetdev.com;
```

Restart nginx server
```
sudo service nginx restart
```