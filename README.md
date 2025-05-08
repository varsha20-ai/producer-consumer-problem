# producer-consumer-problem
Producer-Consumer Problem Simulation using Python Threads and Semaphores  Subtitle: A Simulation of Synchronization in Operating Systems
# Producer-Consumer Problem Simulation using Python

## 📌 Project Description

This project is a simulation of the classic **Producer-Consumer problem**, implemented in **Python** using **threads, locks, and semaphores**. It demonstrates how synchronization is managed in operating systems when multiple threads or processes share a common buffer.

---

## 🧠 Concept

- **Producer** generates items and puts them in a shared buffer.
- **Consumer** takes items from the buffer.
- **Semaphores** ensure producers wait when the buffer is full and consumers wait when it's empty.
- **Locks** provide thread-safe access to the buffer.

---

## 🛠️ Tools Used

- Python
- `threading` module
- `semaphore` & `lock`
- `random` and `time` modules

---

## 💻 Sample Output

Produced: 84 | Buffer: [84]
Consumed: 84 | Buffer: []
Produced: 87 | Buffer: [87]
Consumed: 87 | Buffer: []
...
Processing complete.

---

## 🖼 Output Screenshot

![Output Screenshot](Screenshot%202025-05-02%20192439.png)

---

## 📑 Files Included

- `producer_consumer.py` – Main Python code
- `Producer_Consumer_Report.docx` – Project report
- `Screenshot 2025-05-02 192439.png` – Output screenshot

---

## 🚀 Future Improvements

- Add multiple producers and consumers
- Make buffer size dynamic
- Add GUI to visualize buffer operations
- Include performance measurement

---

## 👩‍💻 Author

- **Name:** A. Varsha  
---

## 📜 License

This project is created for academic purposes. Feel free to use or modify with credit.
