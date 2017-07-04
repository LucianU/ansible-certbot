# certbot
- adds PPA
- installs certbot
- installs certbot cli config
- generates certificate
- sets cron job for auto renewal

## Role Variables

### Required Variables
Variable | Description |
|----------|-------------|
|`certbot_domain`|The domain for which we generate a certificate |
|`certbot_email`|The email address where certbot sends notifications |

### Optional Variables
Variable | Description |
|----------|-------------|
|`certbot_renew_day`|The day when to renew the certificate|
|`certbot_renew_hour`|The hour when to renew the certificate|
|`certbot_renew_minute`|The minute when to renew the certificate|

See `defaults/main.yml` for default values for these variables.


## License
BSD
