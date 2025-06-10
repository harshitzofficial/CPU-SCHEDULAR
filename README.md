## 💻 CPU Scheduling Simulator
---

## 🧠 Project Description

A modern, interactive web application that visualizes and compares various CPU scheduling algorithms.  
Users can dynamically add or remove processes, specify arrival and burst times, and select from multiple scheduling strategies.

The simulator displays:
- A Gantt chart
- A timeline chart
- A final results table with metrics
- An animated time log visualization of process state transitions

---

## ✨ Features

- 🔁 **Add/Remove Processes**: Easily manage processes with customizable arrival and CPU burst times.
- ⚙️ **Supported Algorithms**:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Shortest Remaining Time First (SRTF)
  - Longest Job First (LJF)
  - Longest Remaining Time First (LRTF)
  - Round Robin (RR)
  - Priority Non-Preemptive (PNP)
  - Priority Preemptive (PP)
  - Highest Response Ratio Next (HRRN)
- 📊 **Visualizations**:
  - **Gantt Chart** – Displays CPU scheduling over time
  - **Timeline Chart** – Shows per-process execution periods
  - **Time Log Visualization** – Animated states: Ready, Running, Blocked, Terminated
- 🌗 **Dark Mode** – Toggle between light and dark themes
- 📱 **Responsive Design** – Works on both desktop and mobile devices
- 🏷️ **Process Queue Preview** – Interactive tags show live process queue

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with animations and transitions)
- **JavaScript**
- **Google Charts API** (Gantt, Timeline)
- **Chart.js** (for performance charts)

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/harshitzofficial/CPU-SCHEDULAR
cd CPU-SCHEDULAR

````

### 2. Run the App

Open `index.html` in your browser using a local server like Live Server in VS Code or `http-server`.

### 3. Add Processes

* Click **"Add Process"** to add a row.
* Set **arrival time**, **burst times**, and (if needed) **priorities**.

### 4. Select Algorithm

* Choose a scheduling algorithm from the dropdown.

### 5. Set Preferences

* Toggle **priority preference** (high/low)
* Enter **context switch time** and **time quantum** (for RR)

### 6. Run Simulation

* Click **"Calculate"** to view:

  * Gantt Chart
  * Timeline Chart
  * Results Table
  * Time Log Animation

---

## 📁 File Structure

```
scheduling-algorithms/
├── index.html         # Main interface
├── style.css          # Styling and themes
├── script.js          # Logic and visualization
├── cpu.png            # (Optional) App icon
└── README.md          # This file
```

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/3a304f75-c02f-41d2-9a53-510b49bd3731)


![image](https://github.com/user-attachments/assets/50424a55-2af6-4737-8123-08270a5477d6)

![image](https://github.com/user-attachments/assets/b1428387-3c0c-489e-bfa1-162f3ff907a2)


![image](https://github.com/user-attachments/assets/731bfbd3-6cbd-4f19-be33-207dd487e6f3)

![image](https://github.com/user-attachments/assets/6b5a16ee-21c0-4e38-a7f1-bdafcb6e3d15)

![image](https://github.com/user-attachments/assets/e6f5aba1-622c-48c4-b483-41432661ded3)
![image](https://github.com/user-attachments/assets/3e76eeba-7793-408b-ae12-2e33fec9de7f)







---


## 👨‍💻 Author

**Harshit Singh**

Made with ❤️ by Harshit Singh
