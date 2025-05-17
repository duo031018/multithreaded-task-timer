# Multithreaded Task Timer (C++)

This simple C++ app simulates running multiple tasks in parallel using threads. Each task "runs" for a defined time to demonstrate basic multi-threading and performance measurement.

## Features
- C++ OOP structure (`Task` class)
- Uses `<thread>`, `<chrono>`
- Simulates real-time multi-tasking

## Build Instructions
```bash
make # Or: g++ -std=c++17 -pthread src/main.cpp src/Task.cpp -o task_timer
./task_timer
