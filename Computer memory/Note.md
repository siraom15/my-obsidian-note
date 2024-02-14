### ROM disks such as DVD-ROM 
are **read-only** and the stored data **cannot** be changed or overwritten

### Rewritable disks such as DVD-RAM disks 
are **read-write** and the stored data **can be changed** or **overwritten**.

### Hard disk drive (HDDs)
- can hole up to TB
- used as main storage
- Data access is
	- Fast for [[Sequential access]]
	- Slow for [[Random access]]

Q: 
Suppose you have an HDD where the **sequential access** speed is **100** MB/s, which has an overhead of **10ms** when **accessing a different place** (random access overhead), and further suppose that **files are placed randomly** within the drive and **each file is stored continuously** without any fragmentation.

Which of the following is correct regarding the speed of (A) and (B)?

- (A) read **200** files, **50**kB each (10 MB total)
    
- (B) read **20** files, **500kB** each (10 MB total)

(A): read 200 file means jump 200 times and overheads of jump is 10ms
so 200(files)x10(ms) = **2,000ms** -(1)
and each file contains **50kb** 
so 200(files)x50(kb) =10,000kb = 10MB
sequential access speed = 100MB/s
total 2001ms =2.1s

(B): read 20 file means jump 20 times and overheads of jump is 10ms
so 20(files)x10(ms) = **200ms** -(1)
and each file contains **500kb** 
so 20(files)x500(kb) =10,000kb = 10MB
sequential access speed = 100MB/s
so 10MB/100MB = 0.1s
total 201ms = 0.201s