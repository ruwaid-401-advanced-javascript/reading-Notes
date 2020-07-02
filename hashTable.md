# read 30

## Hashtables
* Hashtables are a data structure that utilize key value pairs.
* every *Node* or *Bucket* has both a *key, and a value*
* *hash*: is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.
*  O(1) time complexity.

## Terminology
- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Why do we use hashtables 
* Hold unique values
* Dictionary
* Library

## Hashing
* hash code turns a key into an integer. 
* very important that hash codes are deterministic
* output is determined only by their input.
* Hash codes should never have randomness
* The same key should always produce the same hash code.

## Creating a Hash
* hashtable traditionally is created from an array
* size 1024. this is important for index placement.

### suggestion for key:
- Add or multiply all the ASCII values together.
- Multiply it by a prime number such as 599.
- Use modulo to get the remainder of the result, when divided by the total size of the array.
- Insert into the array at that index.


## Collisions
collision occurs when more than one key hashes to the same index in an array.