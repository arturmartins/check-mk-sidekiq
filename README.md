check-mk-sidekiq
================

Check_mk sidekiq queue length plugin and check

Requires: redis-cli

Usage:\n 
On Client:\n
 cp mk_sidekiq /usr/lib/check_mk_agent/plugins\n
 chmod 700 /usr/lib/check_mk_agent/plugins\n
On Monitoring Server:\n
 cp sidekiq /usr/share/check_mk/checks
 
