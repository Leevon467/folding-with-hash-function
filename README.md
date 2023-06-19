The hash function used is written in c++ with a non standard header file not compatible with some compilers
 It includes all the standard C++ libraries and some additional ones, which can make the code more concise and convenient
 back to hashing, a good hash should have:
Minimum collision
High gain factor (distributes keys evenly). Like say we have 10 locations in the hash table, then almost 9 locations should have keys. It should not be the case that 4-5 locations have keys only where the keys collided.
Have a high load factor. Load factor means the number of keys stored/hash table size
Easy to compute
