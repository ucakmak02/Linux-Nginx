# Ngnix-Default-Page (Linux System)

### Open Default Page  (probably you should use 'sudo' )
> nano /etc/nginx/sites-available/default

### Change root to:
> root  /usr/share/ngnix/html;

### Change location / to :
> location = / {
>       root /usr/share/nginx/html;
>      index  index.html index.htm;
>  }
