Vagrant provion test
=====

## Files

Vagrantfile	: target Vagrantfile

stdout.log	: vagrant up log(stdout)

debug.log	: vagrant up log(stderrout)

terminal.log	: vagrant ssh log(provision check)

README.md	: this file.


## vagrant up

vagrant up --debug 2>debug.log >stdout.log


## environment

OS Windows 7 professional editon 32bit

Vagrant 1.6.3

Oracle Virtual Box Version 4.3.12 r93733


