**Description:**
The CPU Scheduling Dashboard is a graphical application developed using PyQt5, a Python library for creating desktop applications with a graphical user interface (GUI). This application simulates CPU scheduling algorithms by allowing users to add processes, select scheduling algorithms, and run or stop processes.

**Features:**
1.Add Processes: Users can input process names via a text input field and add them to the list of processes.
2.Select Scheduling Algorithm: Users can choose between Round Robin, First Come First Serve (FCFS), and Shortest Job First (SJF) scheduling algorithms using a dropdown menu.
3.Set Quantum Time: For Round Robin scheduling, users can specify the quantum time for each process.
4.Run and Stop Processes: Users can run processes, which will execute for the specified quantum time (for Round Robin), or until manually stopped. Running processes are displayed with their status, and completed processes are indicated accordingly.

**File Structure:**
cpu_scheduling_dashboard.py: This file contains the main Python script for the application.

**Requirements:**
Python 3.x
PyQt5 library

**Setup:**
Ensure you have Python installed on your system.
Install PyQt5 library if not already installed. You can do this using pip:

**pip install PyQt5**

**Usage:**
1.Run the cpu_scheduling_dashboard.py script.
2.The application window will open, displaying the CPU Scheduling Dashboard.
3.Input process names in the provided text field and click "Add Process" to add them to the list.
4.Select a scheduling algorithm from the dropdown menu.
5.For Round Robin scheduling, specify the quantum time in the corresponding field.
6.Click "Run Process" to execute the selected process according to the chosen algorithm.
7.Click "Stop Process" to manually stop the running process.
8.Monitor the status labels for information on running and completed processes.

**Contributors:**

Developed by Ankur Mukhopadhyay

**Notes:**

This application provides a basic simulation of CPU scheduling algorithms and can be extended with additional features such as visualization of process execution, more scheduling algorithms, and improved user interface design.
