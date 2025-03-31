# Task Scheduler using Priority Queues in C

## Overview
This project implements a **Task Scheduler** using **Priority Queues** in the C programming language. The scheduler manages tasks with different priority levels and executes them based on their priority order.

## Features
- Add tasks with a specified priority
- Remove and execute the highest-priority task
- Display the list of pending tasks
- Uses a **Min Heap or Max Heap** to manage priorities efficiently

## Technologies Used
- **Programming Language:** C
- **Data Structures:** Priority Queue (Heap)

## Installation & Compilation
To compile and run the program, use the following commands:

```sh
gcc task_scheduler.c -o task_scheduler
./task_scheduler
```

## Usage
1. **Add Tasks:** Input task name and priority.
2. **Execute Tasks:** The highest-priority task is executed first.
3. **View Tasks:** Display all pending tasks sorted by priority.
4. **Exit:** Close the scheduler.

## Example
```sh
Enter choice:
1. Add Task
2. Execute Task
3. Display Tasks
4. Exit

> 1
Enter task name: "Backup Data"
Enter priority (1-10): 2
Task added successfully!

> 1
Enter task name: "System Update"
Enter priority (1-10): 1
Task added successfully!

> 3
Pending Tasks:
1. System Update (Priority 1)
2. Backup Data (Priority 2)

> 2
Executing: System Update

> 3
Pending Tasks:
1. Backup Data (Priority 2)
```

## Implementation Details
- **Priority Queue:** Implemented using a **Binary Heap**.
- **Insertion Complexity:** O(log n)
- **Deletion Complexity:** O(log n)
- **Heapify Complexity:** O(n)

## Future Enhancements
- Implement a **GUI-based Task Scheduler**
- Support **Task Scheduling at specific time intervals**
- Implement **Multithreading** for parallel task execution

## License
This project is open-source and available under the **MIT License**.

## Author
{Aditya Sinha}

## Contact 

