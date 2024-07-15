## RAM (Random Access Memory) 
> Computer hardware chip that store data

Characteristics:
* Stores volatile, cache or temporary memory
* Fetches data at a high-speed (faster)
* Stores data for a short period
* Automatically deletes the data if the device is shut off

Use cases:
* Use for copy/pasting
* Opening programs and background processes

## ROM (Read-Only Memory)
> Computer hardware chip that store data

Characteristics:
* Stores non-volatile memory
* Fetches data at a slower-speed
* Stores data for longer periods
* Keeps the data even if the device is shut off

Use cases:
* Computer booting
* Process Initialization

## Hard Drive or Hard Disk Drive (HD or HDD) 
> Is a storage drive made of spinning magnetic plates and a read/write head that reads or writes data

Characteristics:
* Large storage capacity
* Speeds of up to 200MB/S
* Tendency to overheat
* They are best for large, archival activities.

## Solid State Drive (SSD)
> Is the fastest storage option. 

Characteristics:
* It has no moving parts, 
* doesn’t need power to retain data,
* and can read, write, and fetch faster than any HDD
(up to 7000 MB/s, as opposed to 200 MB/s with HDDs
* `Advantages`: Small; Fast; And durable;
* `Negatives`: Expensive with limited capacity and they can fail suddenly

> SSDs are best for activities that require speed, like browsing online, or editing large files.

## Solid-State Hybrid Drives
> Possesses the speed of a SSD but the capacity of a HDD into a single device

> It decides what to store in solid-state vs hard-disk `based on user activity`.

Characteristics:
* Faster than HDDs;
* Offer better performance than HDDs;
* Cost less than pure SSDs;
* Have higher capacities than SSD

> Hard drives and solid-state hybrid drives are sometimes referred to
as Spinning Drives because they use spinning plates to read, write, and fetch data.

## Optical Disk Drives (ODD)
> Optical Disk Drives, or ODDs, read, write,
and store data on optical disks like DVDs, CDs, and BDs (or Blu-ray discs).

How it works:
1. Optical disk drives use a laser to reflect light off a disc’s surface so it can `read` the reflected light
2. The reverse is true when writing to the disk

* Aka: DVD drives/CD drives/BD drives/Disc Drives/Optical Drives

Use Case:
* Optical drives are best for reading large media files stored on discs.

## Flash Drives
> Stores `solid-state drives (SSD)`, but with less energy required as they dont have moving parts that require cooling 

> High-end versions deduplicate and compress data to save space.

> Small, fast and inexpensive to run, `BUT` expensive to purchase and have smaller capacity than hard-disk drives

* Examples: USB drives, Digital memory card

> Flash is best for activities that require speed, like browsing online, or editing files

## Hybrid Disk Arrays 
> Can think of as a `local storage with multiple drives`

> Hybrid Disk Arrays physically combine multiple SSD
and HDD devices into an array of drives working together to achieve `the fast and
easy performance of solid-state` and the lower costs and higher capacities of hard-disk.

* `Pros`: Small, Fast, Lower Setup cost
* `Cons`: Complex to maintain and manage, performance concerns
> Hybrid Disk Arrays are best when you want both fast speeds and high capacity

## Direct-Attached Storage (DAS)
> One or more storage units within an external enclosure that is `directly attached` to the computer accessing it.

DAS can contain:
* Solid State Drives
* Hard Disk Drives
* Optical Disk Drives

Use Cases:
* DAS is best for `small to medium networks` with moderately high storage needs.
* External drives are portable DAS that connect to your computer via USB.

## Ephermeral Storage
> Ephemeral storage `deletes saved data on restart`. It resets things back to their `original state` even if settings, updates, and files are adjusted and saved.

Use Cases:
* App Demos/OS demos in computer labs

## Persisent storage
> Persistent storage `keeps saved data on restart`.

Use Cases:
* Personal Computers and network archives.

> Most storage drives are `configured` to use persistent storage

## Redundant Array of Independent Disks (RAID)
> Spreads data across multiple storage drives working in parallel

#### RAID 0, or Striping
> Splits data into storage units called `blocks` and stores those across 2 or more drives in an array.
* Fast and has 100% usable disk capacity
* `Not fault tolerant`. If 1 drive fails, all data is lost
* Popular with gamers and photographers who need to store `large amts of data` immediately

#### RAID 1 (Mirroring)
> Copies and stores data twice across 2 or more drives
* Cuts space to 50% usable disk capacity
* Fault tolerant. If 1 drive fails, data is `not lost`.

#### RAID 10
* Combines the characteristics of RAID 0 and RAID 1
* Stripes or spreads data across drives that are part of the array.
* RAID 10 is fast, fault tolerant,
* If 3 drives fail, all data is lost.

#### RAID 5 (most common form)
> Striping with parity. It splits data into blocks
and stores those across three or more drives. 
* If data loss occurs, the computer will recalculate
the lost data using error-checking tags known as `parity bits` that it has stored across the drives.
* Parity bits are the `bit flips` that occur due to data loss for error checking. There is `1-D and 2-D parity bit checking`.
* RAID 5 is fast, fault tolerant,
and if 1 drive fails, `no data is lost`.

> RAID devices can use `SSDS, HDDS, and SSHDs`. Companies choose RAID devices for their durability and performance. Multiple drive failure is rare,
but it happens. 

> Maintaining RAID devices, keeping spare drives handy in case of drive failure, and having a backup routine will `make data loss almost impossible`.
