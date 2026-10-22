# PDS_LAB_RECORD_9_Program_20
Explores mutable.HashMap and how hash tables deal with collisions.

Program20_HashMapCollisions.scala

Explores mutable.HashMap and how hash tables deal with collisions.

Creates a HashMap of student names and grades.
Inserts a duplicate key to show that the old value is overwritten.
mergeByHigherGrade - merges two HashMaps; when a key exists in both, the higher grade is kept.
ChainedHashMap - a simple custom hash table that resolves collisions by separate chaining (each bucket stores a list of key-value pairs; the bucket index is name length % buckets).
Retrieves all values stored for a key from the chained table, showing that colliding and duplicate keys are all preserved.

Concepts: mutable.HashMap, pattern matching on Option, hashing, separate chaining, collision resolution
