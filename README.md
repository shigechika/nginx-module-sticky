# nginx-module-sticky

- nginx sticky dynamic module
- Load Blancing Session Persistence Method by Cookie

## How to build

```
rpmdev-setuptree
rpm -Uvh https://nginx.org/packages/centos/7/SRPMS/nginx-1.18.0-2.el7.ngx.src.rpm
git clone https://github.com/shigechika/nginx-module-sticky.git
cd nginx-module-sticky
rpmbuild -ba nginx-module-sticky.spec
sudo yum localupdate /path/to/nginx-module-sticky-1.18.0-2.el7.ngx.x86_64.rpm
```

*See Also

- [Converting the config file for dynamic module](https://bitbucket.org/nginx-goodies/nginx-sticky-module-ng/issues/25/converting-the-config-file-for-dynamic)
- https://bitbucket.org/LeMovieStoreGuy/nginx-sticky-module-ng
- https://github.com/shigechika/nginx-module-pagespeed

## NO WARRANTY

Good Luck :-)
