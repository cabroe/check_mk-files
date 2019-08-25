# check_mk-files

## german translation version 1.5.0p21
wget --no-check-certificate --content-disposition https://github.com/cabroe/check_mk-files/blob/master/multisite.mo?raw=true

mkdir -p /omd/sites/<sitename>/local/share/check_mk/locale/de/LC_MESSAGES
  
cp multisite.mo /omd/sites/<sitename>/local/share/check_mk/locale/de/LC_MESSAGES
