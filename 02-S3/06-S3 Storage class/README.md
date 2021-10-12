#  S3 Storage classes

## SSD-Solid State Drives

1. **S3 standard (Input & output)**- 
    > cost per GB is higher
    > Low Latenancy (faster) 
    > durability =99.999999 %
    > Good performance
    > SSL encryption

2. **S3 Intelligent Tier** (automatically moving data, cost effective)-

    > durability =99.99999999999 %
    > Infrequent data 
    > deep archival data
    > Glacier performance
    > no encryption
    > storage cost is changing

3. **S3 Standard - Infrequent Access -IA** (Long term Storage)-

    > Low price
    > Low Late Nancy 
    > Availability =99.9%
    > SSL encryption
       EX: bank, transactional data

4. **S3 one zone -Infrequent Access**-

    > Lower cost
    > Infrequent access 
    > durability (95%) Availability
    > SSL encryption
    > Availability zone level

## Archival data (HDD - Hard Disc drives)

5.**S3 Glacier** (input output per second)-

    > cost is very very cheaper

6. **S3 Glacier deep Archieve** -

    > very Low, 
    > Long term commitments 
    > Mainly backup and difaster recovery
    > cost is very very cheaper.
    > Retained data you can keep (upto l0 years)
    
*  Real time → Glacier, Glacier deep Archieve-: 2-Long term data

* Standard - Live applications.

