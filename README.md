# nginx-module-sticky

## End of Maintenance Notice

This project is no longer maintained.

With CentOS 7 reaching its end of life, we have decided to retire this repository. No further updates, bug fixes, or new releases will be provided.

We would like to express our sincere gratitude to everyone who has used, contributed to, and supported this project over the years. It has been a wonderful journey, and we truly appreciate your trust and involvement.

Thank you for everything.

---

### About this project (archived)

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
