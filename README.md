<img width="1896" height="904" alt="Screenshot 2025-08-02 180545" src="https://github.com/user-attachments/assets/909d8bba-4d14-4da2-b0aa-82fc4d0ac094" /># Operating System Algorithm Visualizer

# Abstract

This project presents a browser-based educational tool that simulates fundamental operating system algorithms using interactive visualizations. The aim is to help students and learners understand CPU scheduling, disk scheduling, memory allocation, and file system behavior through animation and data-driven output. Built using HTML, CSS, and JavaScript, this tool runs entirely in the browser and does not require any backend or external libraries.

This project is a **simulation and visualization tool for core Operating System algorithms**, built entirely using **Vanilla HTML, CSS, and JavaScript**.

It covers 4 major modules of the Operating System subject:

1. ✅ **CPU Scheduling**
2. ✅ **Disk Scheduling**
3. ✅ **Memory Management**
4. ✅ **Virtual File System**

# Features


### 1️⃣ CPU Scheduling

- Supports:
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - Round Robin (with configurable quantum)
  - Priority Scheduling
- Features:
  - Process table input (Arrival Time, Burst Time, Priority)
  - Real-time Gantt Chart rendering
  - Calculates CT, TAT, WT, RT
  - CPU Utilization, Throughput, Average times
  - Play, Pause, Reset functionality
    
### 2️⃣ Disk Scheduling

- Algorithms:
  - FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK
- Features:
  - Canvas-based disk head movement visualizer
  - Initial head position + custom requests input
  - Displays seek sequence and total head movement
  - Shows algorithm explanation dynamically

### 3️⃣ Memory Management

- Algorithms:
  - First Fit, Best Fit, Worst Fit
- Features:
  - Input memory blocks and process sizes
  - Shows how processes are allocated visually
  - Table showing block-wise allocation
  - Tabbed explanation of each algorithm

### 4️⃣ Virtual File System

- Simulates a real terminal interface in browser
- Supported commands:
  - `mkdir`, `touch`, `rm`, `cd`, `ls`, `pwd`, `tree`, `clear`, `help`
- Fully interactive command-line styled output
- Colored output for files, folders, and errors
- No server required – everything runs in the browser

#Tech Stack

| Technology | Purpose                              |
|------------|---------------------------------------|
| HTML       | Page structure and layout             |
| CSS        | Styling, layout, responsiveness       |
| JavaScript | Core logic for simulations & UI       |
| Canvas API | Used in Disk Scheduling visualizer    |
| DOM APIs   | Used throughout for interactive UI    |

# Key Features

Fully interactive, real-time execution

User-friendly input system

Algorithm explanation section

Statistics display (TAT, WT, CT, etc.)

# Future Enhancements

Add preemptive scheduling (SRTF, preemptive priority)

Add paging and segmentation simulations

Add support for persistent virtual file system

# Conclusion

This project effectively demonstrates core OS algorithms through interactive visualizations. It is a useful learning tool for students and educators alike, and helps bridge the gap between theoretical learning and practical understanding.

<img width="1919" height="884" alt="image" src="https://github.com/user-attachments/assets/507bb8f5-aa3f-4f4f-8e6f-b216c8559916" />

