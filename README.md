# envs.net | finger server

we use `efingerd`

ensure our `/etc/logrotate.d/efingerd`
```bash
/var/log/efingerd.log {
	rotate 5
	daily
	compress
	copytruncate
	missingok
}
```
