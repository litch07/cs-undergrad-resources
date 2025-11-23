# Computer Basics  
**Course:** CSE1110 – Introduction to Computer Systems  
**Topic:** Internal Mechanisms & Architecture

---

## 1. What is a Computer?

A **computer** is a programmable electronic device that follows instructions to solve problems.

**Exam-friendly definition:**

> A programmable electronic device that accepts data (**Input**), processes it according to rules (**Process**), produces results (**Output**), and stores the results for future use (**Storage**).

---

## 2. Information Processing Cycle (IPO Model)

Computers follow a simple universal cycle known as **IPO**.

### 📦 IPO Model Diagram  
*(Add your own image in `/images/ipo_model.png`)*  

![IPO Model](images/ipo_model.png)

### The Steps

1. **Input** – Raw data enters the system (keyboard, mouse, scanner).  
2. **Processing** – CPU converts data into meaningful information.  
3. **Output** – Processed information is presented (monitor, printer).  
4. **Storage** – Information is saved permanently for later use.

💡 **Exam Tip:** If the question asks *“How does a computer work?”* — always start with **IPO**.

---

## 3. Core Hardware Components (Internal Mechanism)

### A. CPU (Central Processing Unit) — *The Brain*

The CPU fetches, decodes, and executes instructions.  
It has **two main units**:

#### 1. Arithmetic Logic Unit (ALU)
- Performs arithmetic operations: `+ - × ÷`  
- Performs logical comparisons: `>, <, =`  
- **Example:** In a game, the ALU calculates hits, damage, and scores.

#### 2. Control Unit (CU)
- Works like *traffic police*  
- Directs the flow of data between ALU, Memory, and I/O devices

---

### B. Primary Memory (RAM) — *The Workbench*

- High-speed temporary memory  
- Stores programs and data currently in use  
- **Volatile:** Data disappears when power is off

---

### C. Secondary Storage — *The Warehouse*

- Permanent storage (HDD/SSD)  
- **Non-volatile**  
- High capacity, slower than RAM

---

## 4. Memory vs Storage (Kitchen Analogy)

- **Storage (HDD/SSD)** → *Grocery Store/Pantry*  
  - Holds everything, but slow to access  
- **RAM (Memory)** → *Kitchen Counter*  
  - Only items needed right now  
  - Fast but limited space

### Comparison Table

| Feature | Primary Memory (RAM) 🧠 | Secondary Storage 💾 |
|--------|-------------------------|------------------------|
| **Speed** | Super fast (ns) | Slower (ms) |
| **Volatility** | Volatile | Non-volatile |
| **Capacity** | Low (8–32GB) | High (256GB–2TB+) |
| **Cost** | Expensive/GB | Cheap/GB |
| **CPU Access** | Direct | Must load into RAM first |

---

## 5. Software Hierarchy

Software acts as the bridge between **user** and **hardware**.

### Two Main Types
1. **System Software** – OS manages hardware (Windows, macOS, Linux)  
2. **Application Software** – User programs (Chrome, Word, VS Code)

### How Software Talks to Hardware

```
      USER (You)
         |
         v
 +------------------+
 |   Application    |  (e.g., Playing a Video Game)
 +------------------+
         |
         v
 +------------------+
 | Operating System |  (e.g., Windows 11)
 +------------------+
         |
         v
 +------------------+
 |  Device Driver   |  (The "Translator" for specific hardware)
 +------------------+
         |
         v
 +------------------+
 |     HARDWARE     |  (Graphics Card / CPU)
 +------------------+

```
---

## 6. Practice Questions (Exam Prep)

### **Q1: Why does a computer need RAM if it has a big Hard Drive?**
Although Hard Drives provide ample space for permanent storage, they are far too slow for the CPU’s processing needs. The CPU requires data to be delivered at lightning speed to function efficiently, which only RAM (Random Access Memory) can provide. Therefore, the computer loads active programs from the slow Hard Drive into the fast RAM so the CPU can access them instantly.

---

### **Q2: Categorize the following:**  
**Monitor, CPU, Keyboard, Hard Drive, Mouse, Printer**

**Answer:**  
- **Input:** Keyboard, Mouse  
- **Process:** CPU  
- **Output:** Monitor, Printer  
- **Storage:** Hard Drive

---

### **Q3: Explain the function of the ALU.**
The Arithmetic Logic Unit (ALU) serves as the CPU's calculation engine. It is responsible for executing all mathematical computations (such as addition, subtraction, multiplication, and division) as well as logical operations (such as comparing values to determine true/false outcomes).

---

## 📝 Keywords

- **Volatile:** RAM  
- **Non-Volatile:** HDD/SSD  
- **Input:** Keyboard, Mouse  
- **Output:** Monitor, Printer  
- **CPU:** Brain of the computer  
- **IPO Cycle:** Input → Process → Output  
- **System Software:** OS  
- **Application Software:** User programs  
