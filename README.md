# bsd-jailguard
FreeBSD jail management tool

## TODO

* validation for at least some config values
* 'guard.create:interface', 'guard.create:ip4.addr', 'guard.from_file:$key:$filepath'
* 'state_check'
* 'state_fix' (both ways)
* restructure code into subdirectories
* use 'log'? + make logs go to a logfile
* templates/images
* absolute paths in config
* 'jailguard' as default interface name
* 'jail_natpass_remove', 'jail_portfwd_delete_all' does not have to check for jail existance - just remove things
* 'guard_reset' command that removes absolutely everything where flags have to be provided:
  --all, --natpass, --portwd, --jail, --base, --netif
