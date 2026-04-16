[Back to Portfolio](./)

Windows Cybersecurity Compliance Check using Python
===============

-   **Class:** CSCI 332 
-   **Grade:** 100
-   **Language(s):** C++
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:csneal@student.csuniv.edu) to request access.)

## Project description

This final project required implementing a complete UDP‑based file transfer system, inspired by Apple’s AirDrop but built from scratch using low‑level socket programming in C++. The goal was to demonstrate reliable data transfer over an unreliable protocol (UDP) by designing a custom packet format and acknowledgment system.
The system consists of two applications:
- UDP Client — reads a file, breaks it into packets, and sends them to the server
- UDP Server — receives packets, reconstructs the file, and saves it to disk

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
# Compile the server
g++ server.cpp -o server

# Compile the client
g++ client.cpp -o client

# Run the server
./server

# Run the client
./client
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

[Back to Portfolio](./)

Windows Cybersecurity Compliance Check using Python
===============

-   **Class:** CSCI 332 
-   **Grade:** 100
-   **Language(s):** C++
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:csneal@student.csuniv.edu) to request access.)

## Project description

This final project required implementing a complete UDP‑based file transfer system, inspired by Apple’s AirDrop but built from scratch using low‑level socket programming in C++. The goal was to demonstrate reliable data transfer over an unreliable protocol (UDP) by designing a custom packet format and acknowledgment system.
The system consists of two applications:
- UDP Client — reads a file, breaks it into packets, and sends them to the server
- UDP Server — receives packets, reconstructs the file, and saves it to disk

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
python compliance_check.py
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Although command‑line based, the program provides a clear and simple interface for sending and receiving files over a network.

Client Tasks
- Enter server IP, port, and filename
- Send the filename to the server
- Transmit file data in 1000‑byte packets
- Display acknowledgment messages from the server
- Notify the user when the transfer is complete

Server Tasks
- Receive the filename and create an output file
- Display each packet received
- Write incoming bytes to disk
- Send "Data" or "Done" acknowledgments
- Notify the user when the file is fully reconstructed

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)

