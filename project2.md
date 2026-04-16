[Back to Portfolio](./)

Large Map
===============

-   **Class:** CSCI 315 
-   **Grade:** 100
-   **Language(s):** c++
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:csneal@student.csuniv.edu) to request access.)

## Project description

This project required designing and implementing a memory-efficient and high-performance map that associates student full names with unique 32-bit unsigned integer IDs. The map supports:
- Fast exact lookups (get())
- Fast prefix-based lookups (howMany())
- Efficient insertion and deletion
- Accurate tracking of size and capacity

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
cd CSCI-315-2026-Spring/
  project1
  make run
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Although the program runs in a command-line environment, it provides a clear and structured interface for interacting with the map. Users can:
- Insert a new name-ID pair
- Retrieve an ID using an exact name
- Count how many names begin with a given prefix
- Remove an entry and free associated memory
- View error messages for invalid or duplicate input
The interface is designed to be simple and readable, making it easy to test performance and correctness on large datasets.  

![screenshot](images/Map_HowMany())  


![screenshot](images/Map_get())  





For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
