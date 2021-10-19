# Storage

* storage is a service 

* Direct (local) attached storage - storage on ec2 host

* Network attached storage - volumes delivered over the network (EBS)

* Ephemeral storage - Temporary storage

* Persistent storage - permanent storage - lives on past the lifetime of the instance

* `Block storage` - volume presented to the OS as a collection of blocks and no structure provided. mountable. bootable

* `File storage` - presented as a file share and has structure. mountable. NOT bootable

* `Object Storage - collection of objects, flat. not mountable. not bootable

## storage types

* SSD - Solid State Drives

* HDD - Hard Disc Drives

| charectaristic | General purpose | Provisioned IOPS | Magnetic
| ----------- | ---------- | --------- | -----------
|                |      SSD        |      SSD        |
| volume size | 1 GiB - 16 tiB | 4 Gib - 16 TiB | 1 GiB - 1 TiB
| maximum throughput | 160 MiB/s | 320 MiB/s | 40-90 MiB/s