# CEPH-Note
Learning CEPH

############## CEPH FileStore ###################################
# ls -l /var/lib/ceph/osd/ceph-12/
total 80
-rw-r--r--   1 root root   481 Jul 17 07:20 activate.monmap
-rw-r--r--   1 ceph ceph     3 Jul 17 07:20 active
-rw-r--r--   1 ceph ceph    37 Jul 17 07:20 ceph_fsid
drwxr-xr-x 510 ceph ceph 16384 Sep 12 03:56 current
-rw-r--r--   1 ceph ceph    37 Jul 17 07:20 fsid
lrwxrwxrwx   1 ceph ceph    58 Jul 17 07:20 journal -> /dev/disk/by-partuuid/a26096c1-d2e0-444a-a2f5-3899443525e7
-rw-r--r--   1 ceph ceph    37 Jul 17 07:20 journal_uuid
-rw-------   1 ceph ceph    57 Jul 17 07:20 keyring
-rw-r--r--   1 ceph ceph    21 Jul 17 07:20 magic
-rw-r--r--   1 ceph ceph     6 Jul 17 07:20 ready
-rw-r--r--   1 ceph ceph     4 Jul 17 07:20 store_version
-rw-r--r--   1 ceph ceph    53 Jul 17 07:20 superblock
-rw-r--r--   1 root root     0 Sep 16 19:25 systemd
-rw-r--r--   1 ceph ceph    10 Jul 17 07:20 type
-rw-r--r--   1 ceph ceph     3 Jul 17 07:20 whoami

# ls -R /var/lib/ceph/osd/ceph-12/ | wc -l
4076

############# CEPH BuleStore ###################################
# ls -l /var/lib/ceph/osd/ceph-2/
total 52
-rw-r--r-- 1 root root 481 Sep 17 11:56 activate.monmap
-rw-r--r-- 1 ceph ceph   3 Sep 17 11:57 active
lrwxrwxrwx 1 ceph ceph  58 Sep 17 11:56 block -> /dev/disk/by-partuuid/874a367f-01cd-475d-a303-e6101c49b0b8
-rw-r--r-- 1 ceph ceph  37 Sep 17 11:56 block_uuid
-rw-r--r-- 1 ceph ceph   2 Sep 17 11:57 bluefs
-rw-r--r-- 1 ceph ceph  37 Sep 17 11:56 ceph_fsid
-rw-r--r-- 1 ceph ceph  37 Sep 17 11:56 fsid
-rw------- 1 ceph ceph  56 Sep 17 11:57 keyring
-rw-r--r-- 1 ceph ceph   8 Sep 17 11:57 kv_backend
-rw-r--r-- 1 ceph ceph  21 Sep 17 11:56 magic
-rw-r--r-- 1 ceph ceph   4 Sep 17 11:57 mkfs_done
-rw-r--r-- 1 ceph ceph   6 Sep 17 11:57 ready
-rw-r--r-- 1 root root   0 Sep 17 11:57 systemd
-rw-r--r-- 1 ceph ceph  10 Sep 17 11:56 type
-rw-r--r-- 1 ceph ceph   2 Sep 17 11:56 whoami

# ls -R /var/lib/ceph/osd/ceph-2/ | wc -l
16
