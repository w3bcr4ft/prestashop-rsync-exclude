# prestashop-rsync-exclude
Prestashop rsync exclude

Exclude files for Prestashop >= 1.5 without product images and htaccess

Cmd : 
//To dev
rsync -Haurov --exclude-from '/path/to/local/exclude/file/rsync-exclude'  remoteServUserName@xx.xx.xx.xx:/path/to/remote/prestashop/ /path/to/local/prestashop/

//To serv
rsync -Haurov --exclude-from '/path/to/local/exclude/file/rsync-exclude' /path/to/local/pestashop/ remoteServUserName@xx.xx.xx.xx:/path/to/remote/prestashop/
