CheckOutSystem.CPP
=====================

## Description

A program for implementing a simple supermarket checkout with two special offers:
- buy 3 identical items and pay for 2
- buy 3 (in a set of items) and the cheapest is free

## Prerequisites
The program reads an item index file that is specified at runtime. The index file must contain lines corresponding to each item in the format
<integer item code>     <item name (string)>    <item price>    <offer identifier (string)>

Each column must be separated by tabs.


usage:
    
* g++ main.cpp CheckOutSystem.cpp 
* ./a.out -f /Users/aesthetic/Desktop/Submission/item_index.txt



## Built With:
* C++

## Authors

* **Osato Osagie** 


## software artefacts
* CheckOutSystem.cpp
* Transaction.h
* item_index.txt
* main.cpp


