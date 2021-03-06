# Bazooka Share
Secure Peer-based Environments in Equitable Decentralization

[Find the repository here](https://github.com/astrosonic/bazooka-share/)

<p align="center">
    <img src="https://img.shields.io/github/issues/astrosonic/bazooka-share?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/forks/astrosonic/bazooka-share?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/stars/astrosonic/bazooka-share?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/license/astrosonic/bazooka-share?style=flat-square&logo=appveyor&color=teal">
</p>

## Decentralised Union of Connected Environments (DUCE)

### Base program for node implementation v0.1

1. UDP base communication with full control.
2. On-the-go change of connection head.
3. Asynchronous action implemented.
##### (DAB)

### Bazooka v0.0.1

1. Create seeder/psuedo seeder/peer type of node in the network.
2. Using special type of architecture to co-ordinate the work for the sudo-seeders/peer nodes.
3. Tier jumping is enabled in the implementation.

### Bazooka v0.0.2

1. Base program with Node.py usage
2. Updated Node.py as initial declaration and later usage in peer.py
3. 1st Tier implementation done without interconnection.

### Bazooka v0.0.3 [Upcoming]

1. 1st Tier interconnection finalization.
2. Shadow clone teaser (Maybe?)


## File Archive Dispersal and Encryption (FADE)

### Changelog

### v0.01
#### FADE Legacy (Deprecated)
1. Dynamic file naming based on number of split parts
2. Size allocation to parts for the given part count
3. Enabled SHA512 hashing by default for all the parts
4. CLI shows block names, block sizes and hash values
5. Capable of upto 999 parts - Going beyond is crazy

### v0.02
#### FADE Legacy (Deprecated)
1. Uses `colorama` for some funky CLI
2. Ledgers with block names, block sizes and hash values
3. Ledger reading and display for auditing purposes
4. Block collection health checkup for missing or corrupted files
5. Joining of files when health checkup returns positive
6. Uses `os` for ledger and block deletion from system
7. Automatic removal of ledger and blocks when joining complete

### v0.03
#### FADE Legacy (Deprecated)
1. Switched default accent from GREEN to CYAN
2. Fragment capacity increased to 9999 blocks - Going beyond is stupid
3. Fixed issue when block count greater than byte size was accepted
4. Fixed issue when block count equal to 100 was not accepted
5. Fixed issue when requested file for splitting was not found
6. Fixed issue when requested ledger for joining was not found
7. Refactored code for optimised calculation
8. Added percentage progress display for joining/splitting

### v0.04
#### FADE Legacy (Deprecated)
1. Reduced visibility of progress percentage and block size
2. Disposed off allocation by size in favour of allocation by count
3. Ledger display invokable by filename - ledger name not needed
4. Added timer for long thread operations
5. End-of-life for function-only based implementation (aka FADE Legacy)

__Note__ : Only bug fixes for existing features would be provided for FADE Legacy. No new features would be implemented. It is highly recommended to move on to a faster class based implementation v0.05 (aka FADE Modern).

### v0.05 [Current]
#### FADE Modern
1. Fast and optimised object-based implementation
2. Better memory address exception handling
3. Deprecated allocation by size function was removed
4. Disposed off ledger read function in favour of internal constructor
5. Block collection health checkup is now Block Integrity Check
6. Reduced overhead due to minimal disk reads. Following operations are faster - displaying ledger audits or block integrity check operations
7. Removed ledger list metadata in favour of a set of class-wide variables
8. Reduced split operation to one-third of the original instruction length
9. Efficient memory utilization with dynamic objects

### v0.06 [Oncoming]
#### FADE Modern
1. Fixed issue of arbitration of two same named functions in a class
2. Fixed issue of joining when non-existent ledger was referenced
3. Added back splitting and joining by size
4. Introduced two types of ledgers - Split by Count (SBC) and Split by Size (SBS)
5. Fixed invalid reference to join class when ledger was invalid or corrupt
6. Split by size limit is between 1MB to 8MB block size