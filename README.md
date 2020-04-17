# HashTable 0.1
Built with GCC9-C++20 on Manjaro.

# Basic interface
Contains a basic interface in main.cpp to use a basic implementation of these functions.

# Functions
* Class Entry
  
  - Two data members: key, value
  - Constructor taking both data members.

* Class HashMap
  
  - 2D Array HashTable for storage
  - vSize containing size of the array
  - Constructor taking the size and generating as many slots as the given size.
  - keyMod - takes a key and returns it's probable position in the array. 
  - insertion and extraction is handled with square brackets and the iostream library. 
  - removeKey - removes the first instance of that key.
  - removeValue - removes a given value from the whole list.
  - searchKey - searches for a key and returns it's position.
  - searchValue - seraches for a value and returns it's position.
  - size - returns vSize.
