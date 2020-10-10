Goal: Our goal is to take in strings as the input, convert them to keys and the insert
them into a hash table using the power of two choices.

The Process: 
The strings are entered either as user-input, hard-coded or randomly-generated strings.
Whatever the method, a hash object is created using the size declared by the user to
created a Linked List representing the Hash Table. And for each index of the Linked List, a
Linked List is created which represents Collision Handling.

The strings are then placed in an Insert function which converts them, using two
independent hash functions, into two keys. The keys are then compared w.r.t the Hash
Table to find out which “bucket” has fewer strings and is the placed in that “bucket”.