# 🖥️ Operating Systems Simulator – 4 Module Project

A Streamlit-based interactive simulator for core Operating Systems concepts, including memory management, CPU scheduling, process synchronization, and disk scheduling. This project was developed using Python to visualize and better understand key OS algorithms in a hands-on manner.

---

## 📁 Modules Included

### 1️⃣ Optimal Page Replacement
- Simulates the **Optimal Page Replacement Algorithm**.
- Displays current page table status and page faults dynamically.
- Includes a Gantt-like visualization of page requests and faults.

### 2️⃣ Producer-Consumer Problem (Using Monitors)
- Implements the classic **Producer-Consumer synchronization** problem.
- Utilizes Python threading, `Condition` objects, and `Queue` to simulate shared buffer access.
- Real-time Streamlit UI to monitor production and consumption of data.
  
### 3️⃣ SRTF (Shortest Remaining Time First) Scheduling
- Simulates **CPU scheduling** using the preemptive SRTF algorithm.
- Accepts manual input or CSV file for process details.
- Calculates and displays:
  - Completion time
  - Turnaround time
  - Waiting time
- Visual Gantt chart for scheduling timeline.

### 4️⃣ SSTF (Shortest Seek Time First) Disk Scheduling
- Simulates **Disk Head Movement** using SSTF.
- Visualizes the order of servicing track requests.
- Displays total head movement and the sequence of access.

---

## 🛠️ Technologies Used
- **Python**
- **Streamlit** (Interactive UI)
- **Matplotlib** (Visualization)
- **Pandas** (CSV handling and data tables)
- **Threading, Queue** (for synchronization problems)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/os-simulator.git
   cd os-simulator
2. Install required dependencies:
  ```bash
  pip install -r requirements.txt
```
3. Run each module individually:
  ```bash
  streamlit run optimal_page_replacement.py
  streamlit run producer_consumer.py
  streamlit run srtf_scheduler.py
  streamlit run sstf_disk_scheduling.py
```
