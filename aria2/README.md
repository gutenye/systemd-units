## Install

	$ mkdir -p ~/.config/aria2
	$ edit ~/.config/aria2/aria2.conf
	  dir=/home/USER/Downloads
	  rpc-secret=SECRET            # you can generate a secret by `< /dev/urandom tr -dc _A-Z-a-z-0-9 | head -c32`
	$ touch ~/.config/aria2/session.lock
	# cp aria2.service /etc/systemd/user

## Usage

	$ systemctl --user start aria2
	$ systemctl --user stop aria2
	$ systemctl --user restart aria2
	$ systemctl --user status aria2

## Configuration

Edit `~/.config/aria2/aria2.conf` and read `man(aria2c)` for references.
