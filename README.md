# Nginx config files

## Files

- `nginx/includes/le.conf`: letsencrypt
- `nginx/includes/ssl.conf`: for "A+" Qualys SSL Labs rating
- `nginx/includes/security.conf`: XSS filter + basic stuff to get rid of skids
- `nginx/sites-avaialble/default`: default server config
- `nginx/sites-avaialble/example`: example server config
- `cron.weekly/certbot`: crontab for letsencrypt auto renewal

## Setup

openssl dhparam -out /etc/nginx/dhparam.pem 2048
