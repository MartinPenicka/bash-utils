

LOCKTIME=10
UNLOCKTIME=8

all:
	mkdir `$HOME`/bin
	ln -s weblock `$HOME`/bin/weblock
	chmod a+x `$HOME`/bin/weblock
	cat /etc/hosts > "`pwd`/hosts.backup"
	sudo echo "#WEBLOCK FORBIDDEN" >> /etc/hosts
	sudo echo "#WEBLOCK LOCKED" >> /etc/hosts
	# add item to cron
	# add item to cron