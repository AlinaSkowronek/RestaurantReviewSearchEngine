# Restaurant Review Hash Table

Author: Alina Skowronek  
Language: C++  
Project Type: Data Structures / Hash Table

---

## Project Overview
This project implements a system for storing and retrieving restaurant reviews using a hash table data structure. Reviews are inserted, hashed, and retrieved efficiently by key. This project demonstrates understanding of hashing, collision resolution, and data organization in C++.

---

## How to Compile & Run

### Compile
```bash
g++ -Werror -Wall -Wpedantic -std=c++17 <your .cpp files here> -o RestaurantReviewHashTable
```

## Dependencies
Make sure the following files are present in the same directory as your source code (modify this list based on your repo structure):

- HashTable.hpp
- Review.hpp
- MainDriver.cpp
- Any input files (e.g., restaurants.txt, reviews.txt)

---

## Features
- Insert restaurant reviews into a hash table
- Lookup reviews by key
- Collision handling (chaining or open addressing)
- Load factor calculations
- Display and debugging functions

---

## Design & Implementation Notes
- Hash function ensures uniform distribution of keys
- Collision resolution implemented through chosen strategy
- Modular class structure (Review, HashTable, Driver)
- Supports dynamic or fixed table sizes depending on implementation

---

## How to Test
1. Compile using the provided command.
2. Run the executable.
3. Insert reviews manually or load them from an input file.
4. Test lookup, insertion, and search operations.
5. Observe collision handling and load factor behavior.

---

## License
Created by Alina Skowronek.  
Use permitted for learning and academic purposes. Commercial or redistributed use requires permission.

---

## Future Improvements
- Add persistent file storage (save/load hash table)
- Test multiple hash functions for comparison
- Create a GUI or web interface for viewing reviews
- Add sentiment analysis for review text

