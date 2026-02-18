# Lab_02_Pointers

**Overview**

The repository contains three primary exercises that progress from basic pointer syntax to the implementation of dynamic data structures. Each exercise highlights the importance of manual memory management using the new and delete operators.

**Features**

- **Pointer Arithmetic:** Accessing and modifying variables through memory addresses rather than variable names.
- **Dynamic Variables:** Allocating memory for single integers and character arrays during runtime.
- **Dynamic Arrays:** Creating arrays whose size is determined by user input, allowing for optimized memory usage.
- **Manual Deallocation:** Using delete and delete[] to free memory and prevent memory leaks.

**Experiment & Results**

**Experiment 1:** Pointer Basics

- **Objective:** Use pointers to calculate the area of a rectangle and compare dimensions.
- **Key Logic:** Accessing values via the dereference operator (*lengthPtr) and addresses via the address-of operator (&length).
- **Result:** Successfully calculated area and determined which dimension was greater using only pointer variables.
- 
**Experiment 2:** Dynamic Variables
  
- **Objective:** Allocate memory for three integers and a 10-character name array on the heap.
- **Implementation:** Used new int and new char[MAXNAME] to request memory.
- **Result:** The program echoed the user's name and calculated the sum of three dynamically stored integers.
- 
**Experiment 3:** Dynamic Sales Array
  
- **Objective:** Process monthly sales data where the number of months is defined by the user.
- **Calculation:**
- **Total Sales:** $\sum Sales_{i}$
- **Average:** $\frac{Total}{Count}$
- **Result:** In a test case with 3 months (sales of 20, 13, and 47), the program correctly calculated an average monthly sale of $26.67.

**Technologies**

**Language:** C++
**Standard Libraries:** iostream, iomanip (for currency formatting), math.h.
**Key Concepts:** Dereferencing, Address-of operator, Heap allocation, Memory Leaks, Null pointers.

**Project Structure**

**main1.cpp:** Exercise on basic pointer usage.
**main2.cpp:** Exercise on dynamic variable allocation.
**main.cpp:** Exercise on dynamic array processing for sales data.
**lab3_pointers.pdf:** Laboratory manual with theory and tasks.
**report_lab02_...pdf:** Full documentation of screenshots and verified results.

