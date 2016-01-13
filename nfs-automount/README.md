Install
------

```
# cp nfs-automount.service nfs-automount.timer /etc/systemd/system
# cp nfs-automount /etc/systemd/scripts
```

Usage
-----

```
# edit /etc/fstab

  box:/music        /mnt/music         nfs noauto,noatime,rsize=32768,wsize=32768 0 0

# systemctl start nfs-automount.timer
```
