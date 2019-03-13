# linc_corp

How to update SSL Certificate:

```sh
# linc-info.com
sudo letsencrypt certonly -m support@linc-info.com --agree-tos --non-interactive --webroot -w /home/deploy/linc_corp/public -d linc-info.com --force-renewal

# www.linc-info.com
sudo letsencrypt certonly -m support@linc-info.com --agree-tos --non-interactive --webroot -w /home/deploy/linc_corp/public -d www.linc-info.com --force-renewal
```