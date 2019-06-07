# MinIO - Docker

**WIP!**

A few helper files and notes to setup and run minio, for easy deploy and reference.

### Links:

 - https://github.com/minio/minio
 - https://github.com/minio/mc
 - https://hub.docker.com/r/minio/minio
 - https://www.npmjs.com/package/minio

### Setup

...


### Start

`bash start.sh`


### Cron

```
SHELL=/bin/sh
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin

@reboot cd /var/www/html && bash ./start.sh -s >> ./console.log 2>&1
```

### Clean

`bash clean.sh`


### Things I forget

**add host**

`mc config host add minio http://<SERVER_IP> 123456-access 123456-secret`
