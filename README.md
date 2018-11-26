An ansible role installing a cron to renew Let's Encrypt certificates

# Warning

Due to conflicts between Apache HTTD and Nginx packages on Debian distribs,
this role does not manage Nginx renew on Debian.