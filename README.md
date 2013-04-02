php-netio-rcswitch
==================

Using a fake netio-device api to control rcswitch command line remotely

For example to be used with rcswitch-pi (https://github.com/r10r/rcswitch-pi) and Power Outlets (https://itunes.apple.com/app/power-outlets-power-control/id447756862) to allow remote switching over a raspberry.

It is necessary to enable sudo access for the rcswitch command for non-root or just www-data explicitly.

To set up:
- upload control.tgi to a path of your choice but make it accessable via server:80/tgi/control.tgi
- make sure the command line is correctly configured
- e.g. test with server:80/tgi/control.tgi?p=uu1u