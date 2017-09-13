# ilias-configs-public

**Contact:** [Daniel Weise](https://github.com/daniwe4), [Richard Klees](https://github.com/klees)

This repo contains configuration files for [ilse](https://github.com/conceptsandtraining/ilias-tool-ilse).

To use them you need to add a minimal configuration fail that contains your local
locations and credentials:

```
---
client:
    data_dir:  /home/rklees/ilias-install/ilse/data
database:
    host: localhost
    user: USER 
    password: PASSWORD
server:
    http_path: http://localhost/ilse
    absolute_path: /home/rklees/ilias-install/ilse/www
setup:
    master_password: MASTER_PASSWORD
log:
    path: /home/rklees/ilias-install/ilse/logs 
    error_log:  /home/rklees/ilias-install/ilse/logs
```

You may also want to use [doil](https://github.com/conceptsandtraining/ilias-tool-doil),
which will install ILIAS in a docker environment and thus generate that file for you.

