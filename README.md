Introduction
---

Author: Yuanyuan Sun,  Ling Yang
Date: 2015-05-27
Version: 1.0

This is a simple implementation of MinCounter algorithm. For more details about MinCounter algorithm,  you can read our paper "MinCounter: An Efficient Cuckoo Hashing Scheme for Cloud Storage Systems" on MSST 2015.


### Usage  

- Compile 
    `$g++ cuckoo-main.cpp -o cuckoo`
- Run 
    `./cuckoo max_loop init_rate file_name`

    Parameters: 
    * max_loop: when inserting a new element, if the times of kick out elements equals to max_loop, we think there are a infinite loop.
    * init_rate: when initiate the hash table, we set the size of hash table equals to the size of dataset  multiplied by init_rate.
	* file_name: file_name is the name of dataset file.


### Reference

- [Cuckoo hash map](http://sourceforge.net/projects/cuckoo-cpp/?source=navbar)

