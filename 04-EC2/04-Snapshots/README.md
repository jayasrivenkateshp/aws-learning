# Snapshots

* `Snapshot` is a backup of EC2 instance `volumes`

* snapshots can be used to migrate data to different availability zones in a region, or to different regions of AWS

* snapshots are incremental volume copies to S3

* the first is a full copy of `data` on the volume

* future snaps are incremental

* volumes can be created (restored) from snapshots

* snapshots can be copied to another region

* new EBS volume = full performance immediatly

* `upto 50 snaps per region`