# galledanza-pkg
Self-installing package to automatically set user defined commands &amp; preferences (aliases, etc...)

## setting up email alerts

1. goto & edit the folllowing `vi /etc/exim4/update-exim4.conf.conf` 
2. just change the following from `local` to `dc_eximconfig_configtype='internet'`
3. don't forget finally to launch `/etc/init.d/exim4 restart` 

