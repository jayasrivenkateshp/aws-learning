# Elastic Block Store (EBS)

* EBS ia a service 

* `Create, attach volumes` through an existing EC2 and API

* Without EC2 instance no value for EC2 instance

* you can add upto `25 EBS volumes` to 1 EC2 instance (26 Alphabets)

* `Volumes persist to 1 EC2`

* you cannot attach same volume to different EC2 instance

* `Detach and attach between instances`

* `volume and instance must be in the same AZ`

* you can attach one EBS volume to one EC2 instance at a time

* Block Storage - disk allocations (volume) - Can be encrypted using KMS

* instances see block device and create file system on this device (ext3/4, xfs)

* `Storage is provisioned in ONE AZ (Resilient in that AZ)`

* Attached to *one EC2 instance (or other service) over a storage network

* detached and reattached, not lifecycle linked to one instance.. persistent

* Snapshot (backup) into S3. Create volume from snapshot (migrate between AZs)

* Different physical storage types, different sizes, different performance profiles

* Billed based on GB-month (and in some cases performance)

## EBS volume types

* SSD - Solid State Drives

* HDD - Hard Disc Drives

| charectaristic | General purpose | Provisioned IOPS | Magnetic
| ----------- | ---------- | --------- | -----------
|                |      SSD        |      SSD        |
| volume size | 1 GiB - 16 tiB | 4 Gib - 16 TiB | 1 GiB - 1 TiB
| maximum throughput | 160 MiB/s | 320 MiB/s | 40-90 MiB/s
| IOPS performance | 3 IOPS / GiB upto (10,000 IOPS) | provisioned level upto 20,000 IOPS | average 100 IOPS with 
|                    |  3000 IOPS for volumes under 1000 GiB | maximum , very costly | ability to burst, low cost
| API and CLI volume name | gp2 | io1 | standard

## Volume types

* General purpose (gp2)  - SSD
* General purpose (gp3)  - SSD
* provisioned IOPS - SSD
* magnetic - SSD
* throughput optimized - HDD
* cold HDD