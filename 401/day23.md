# Day 23 Notes

## Hashtables

### My Hashtables Cheat-Sheet

**Basics:**

1. Hashtable is a data structure that implements an associative array abstract data type, a structure that can map keys to values.

2. Python has built-in support for hash tables with dict data type.

3. Hash tables work by computing an index into an array of buckets or slots, from which the desired value can be found.

4. The key must be hashable i.e., it must have a hash value which does not change during its lifetime (immutable).

**Operations:**

> Create

1. d = {} creates an empty dictionary

2. d = {key1: value1, key2: value2, ...} creates a dictionary with keys and values.

> Access

1. d[ key ] returns the value for the given key.

2. key in d returns True if the key exists in the dictionary.

> Add/Update

1. d[ key ] = value updates the value for the given key. Adds the key-value pair if the key doesn't exist.

> Delete

1. del d[ key ] removes the key-value pair for the given key.

2. d.pop(key, default) removes and returns the value for the given key. Returns default if key doesn't exist.

> Iterate

1. for key in d loops through the keys in the dictionary.

2. for key, value in d.items() loops through the keys and values in the dictionary.
Hash collision

3. When two or more keys have the same hash value, it's called a hash collision.

4. Python handles hash collisions with chaining, where each bucket is a linked list of key-value pairs with the same hash value.

#### Things I want to know more about

> How to effectively use hashtables

Click to return [Home!](../README.md)
