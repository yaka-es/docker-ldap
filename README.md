# docker-ldap
Dockerized minimal openldap-server installation based on Alpine Linux.

Do not use this build!

Basic usage:

```
$ docker run --rm -it \
	-v /mnt/docker/ldap-server/etc/openldap:/etc/openldap \
	-v /mnt/docker/ldap-server/var/lib/openldap-data:/var/lib/openldap-data \
	yakaes/docker-kdc
```

