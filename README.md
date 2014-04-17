EC440 homework to create a device using kernel commands

To test, run the following commands

```
make
insmod ./hw7.ko
mknod /dev/chardev c 248 0
cat /dev/chardev
echo 10 > /dev/chardev
cat /dev/chardev
```

