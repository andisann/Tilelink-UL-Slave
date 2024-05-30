# Tilelink-UL-Slave
This repository contains a slave interface for communicating with RISCV cores that implement the TileLink protocol (Version 1.9.3).

The slave contains 16 registers of 32 bits. It implements Get, PutFull and PutPartial operations with logic for verification if the Master is trying to write in unaligned directions. 
