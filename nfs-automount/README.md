```
# edit /etc/fstab

  box:/music        /mnt/music         nfs noauto,noatime,rsize=32768,wsize=32768 0 0

# ./install
# systemctl enable nfs-automount.timer
```
