
Task Scheduler Using Priority Queues in C
Introduction
This project is a Task Scheduler implemented in C, utilizing Priority Queues to efficiently manage and execute tasks based on their priority levels. The scheduler ensures that tasks with higher priority are executed before lower-priority ones.

Features
Implements a priority queue using a heap or linked list.
Allows adding tasks with different priority levels.
Executes tasks in order of highest priority.
Supports task deletion and modification.
C Programming Language
Priority Queue (Heap or Linked List)
Dynamic Memory Allocation
How It Works
Task Structure:
Each task contains:

Task ID
Description
Priority (higher value means higher priority)
Execution time
Priority Queue Implementation:

Tasks are stored in a heap (min-heap or max-heap).
Higher priority tasks are dequeued first.
Supports insertion, deletion, and peek operations.
Scheduler Execution:

Users can add tasks with specific priority levels.
The scheduler retrieves the highest-priority task and executes it.
Completed tasks are removed from the queue.
