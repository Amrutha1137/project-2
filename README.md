# project-2
# Hospital Patient Queue

## 📌 Project Description
This project simulates a hospital patient queue system. The main goal is to manage patients based on their urgency. Critical patients get higher priority while normal patients are served in the order they arrive. The system also calculates the estimated waiting time.

---

## ⚙️ Features
- Add new patients with details (name, type, service time).
- Priority queue for critical patients.
- FIFO queue for normal patients.
- Display estimated wait time for all patients in the queue.
- Interactive menu system.

---

## 🖥️ How It Works
1. **Add Patient** – Enter patient name, critical status, and service time.
2. **Serve Patient** – Serves critical patients first, otherwise normal patients.
3. **Show Estimated Wait Time** – Displays total time needed to serve all patients waiting.
4. **Exit** – Ends the program.

---

## 🛠️ Tech Used
- Language: **C++**
- Data Structures:
  - **Priority Queue** (for critical patients)
  - **Queue** (for normal patients)

---

## 🚀 How to Run
1. Save the code in a file named `hospital_queue.cpp`.
2. Compile using:
   ```bash
   g++ hospital_queue.cpp -o hospital_queue

