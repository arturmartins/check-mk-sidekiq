check-mk-sidekiq
================

Check_mk sidekiq queue length plugin and check

Requires: redis-cli

Usage:

On Client:
 
	cp mk_sidekiq /usr/lib/check_mk_agent/plugins
 
	chmod 700 /usr/lib/check_mk_agent/plugins

On Monitoring Server:
 
	cp sidekiq /usr/share/check_mk/checks
 
