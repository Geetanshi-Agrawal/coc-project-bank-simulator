# coc-project-bank-simulator
🏦 Project Title: The Bank Queue (Poisson) Simulator

📘 Description

This project simulates how customers arrive and are served in a bank during an 8-hour day.
It uses probability and random events to model real-life customer arrivals and teller service times.
The goal is to help the bank analyze average wait times, queue lengths, and teller performance to decide if another teller is needed.

💡 Concepts Used

C Concepts:
Loops and functions
Structures and arrays
Random number generation
Dynamic memory (malloc, free)
Time-based seeding (time.h)

Math Concepts:
Poisson distribution (customer arrivals)
Exponential distribution (service times)
Mean and probability calculations

⚙️ How to Compile
gcc bank_queue.c -o bank_queue -lm

▶️ How to Run
./bank_queue
