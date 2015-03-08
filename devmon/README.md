[udevil](http://ignorantguru.github.io/udevil/) is a command line Linux program which mounts and unmounts removable devices without a password, shows device info, and monitors device changes.

## Install

	# cp devmon@.service /etc/systemd/system
	# cp devmon /etc/conf.d

## Usage

	# sytemctl start devmon@<user>
