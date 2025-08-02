# Operating System Algorithm Visualizer

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

 sample input

 | PID | Arrival Time | Burst Time | Priority |
| --- | ------------ | ---------- | -------- |
| P1  | 0            | 5          | 2        |
| P2  | 1            | 3          | 1        |
| P3  | 2            | 8          | 3        |

<img width="1896" height="904" alt="Screenshot 2025-08-02 180545" src="https://github.com/user-attachments/assets/a1885716-aaeb-46a4-8f47-fc582e30af7c" />
<img width="1891" height="902" alt="Screenshot 2025-08-02 180555" src="https://github.com/user-attachments/assets/371694e0-04e1-45d0-8ab9-74f2069d9c2c" />

### 2️⃣ Disk Scheduling

- Algorithms:
  - FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK
- Features:
  - Canvas-based disk head movement visualizer
  - Initial head position + custom requests input
  - Displays seek sequence and total head movement
  - Shows algorithm explanation dynamically
 
  sample input-
  
Initial Head Position: 53

Request Queue: 98, 183, 37, 122, 14, 124, 65, 67

Disk Size: 200
<img width="1916" height="815" alt="Screenshot 2025-08-02 180708" src="https://github.com/user-attachments/assets/bc8790ac-4e4b-434c-92af-38cb06398e36" />
<img width="1900" height="885" alt="Screenshot 2025-08-02 180724" src="https://github.com/user-attachments/assets/63c9c106-ca5e-432e-a093-0823d3a6197f" />

### 3️⃣ Memory Management

- Algorithms:
  - First Fit, Best Fit, Worst Fit
- Features:
  - Input memory blocks and process sizes
  - Shows how processes are allocated visually
  - Table showing block-wise allocation
  - Tabbed explanation of each algorithm
 
Sample Input:
Memory Blocks: 100, 500, 200, 300, 600

Processes: 212, 417, 112, 426

<img width="1896" height="878" alt="Screenshot 2025-08-02 180825" src="https://github.com/user-attachments/assets/0ac77c59-c59e-41d2-be62-6f70c09b64cb" />
<img width="1495" height="805" alt="Screenshot 2025-08-02 180838" src="https://github.com/user-attachments/assets/da821d59-0714-404d-86cb-5618b0317d6d" />

### 4️⃣ Virtual File System

- Simulates a real terminal interface in browser
- Supported commands:
  - `mkdir`, `touch`, `rm`, `cd`, `ls`, `pwd`, `tree`, `clear`, `help`
- Fully interactive command-line styled output
- Colored output for files, folders, and errors
- No server required – everything runs in the browser

cammand executed-

mkdir docs  

cd docs  

touch file1.txt  

mkdir code  

ls

<img width="1203" height="763" alt="Screenshot 2025-08-02 181459" src="https://github.com/user-attachments/assets/e085cf08-de79-4006-b85d-8931f846082d" />
<img width="1268" height="800" alt="Screenshot 2025-08-02 181506" src="https://github.com/user-attachments/assets/11a1bd8a-f638-411b-895f-4a384b55c68f" />

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

