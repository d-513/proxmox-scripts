# proxmox-scripts

## stress test

```
# terminal #1
apt install stress xsensors
stress --cpu <number of cores or threads if hyperthreading is enabled>
# terminal #2
watch -n .1 sensors
```
