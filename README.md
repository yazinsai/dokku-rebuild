## [Dokku](https://github.com/progrium/dokku) plugin to rebuild an app without a git push

Commands
--------
```
$ dokku help
     rebuild <app>     Rebuilds specified app
     rebuild:all       Rebuilds all apps
```

Installation
------------
```bash
cd /var/lib/dokku/plugins
git clone https://github.com/scottatron/dokku-rebuild rebuild
dokku plugins-install
```

Tagged releases are compatible with the equivalent Dokku release e.g. Dokku v0.2.x / Dokku Rebuild v0.2.x
