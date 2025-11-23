# Internal Mechanism of Computer

**Course:** CSE1110 – Introduction to Computer Systems  
**Topic:** Internal Mechanisms & Architecture

---

## 💻 What is a Computer?

A **computer** is a programmable electronic device that follows instructions to solve problems.

### Exam-Friendly Definition

> A programmable electronic device that accepts data (**Input**), processes it according to rules (**Process**), produces results (**Output**), and stores the results for future use (**Storage**).

---

## 🔄 Information Processing Cycle (IPO Model)

Computers follow a simple universal cycle known as **IPO**.

```
┌─────────────┐         ┌───────────────────────────┐         ┌──────────────┐
│   INPUT     │ ──────> │       PROCESSING          │ ──────> │    OUTPUT    │
│ (Keyboard,  │         │     (CPU + Memory)        │         │   (Monitor,  │
│   Mouse)    │         │                           │         │   Printer)   │
└─────────────┘         └───────────────────────────┘         └──────────────┘
                                      │  ▲
                                      │  │
                                      ▼  │
                               ┌──────────────┐
                               │   STORAGE    │
                               │  (SSD, HDD)  │
                               └──────────────┘
```

### The Four Steps

**⌨️ Input** – Raw data enters the system (keyboard, mouse, scanner)

**⚙️ Processing** – CPU converts data into meaningful information

**🖥️ Output** – Processed information is presented (monitor, printer)

**💾 Storage** – Information is saved permanently for later use

> 💡 **Exam Tip:** If the question asks *"How does a computer work?"* — always start with **IPO**.

---

## 🔧 Core Hardware Components (Internal Mechanism)

### 🧠 CPU (Central Processing Unit) — *The Brain*

The CPU fetches, decodes, and executes instructions. It has **two main units**:

#### ➕ Arithmetic Logic Unit (ALU)

- Performs arithmetic operations: `+`, `-`, `×`, `÷`
- Performs logical comparisons: `>`, `<`, `=`
- **Example:** In a game, the ALU calculates hits, damage, and scores

#### 🚦 Control Unit (CU)

- Works like *traffic police*
- Directs the flow of data between ALU, Memory, and I/O devices

---

### ⚡ Primary Memory (RAM) — *The Workbench*

- High-speed temporary memory
- Stores programs and data currently in use
- **Volatile:** Data disappears when power is off

---

### 🗄️ Secondary Storage — *The Warehouse*

- Permanent storage (HDD/SSD)
- **Non-volatile**
- High capacity, slower than RAM

---

## 🍳 Memory vs Storage (Kitchen Analogy)

- **🏪 Storage (HDD/SSD)** → *Grocery Store/Pantry*  
  Holds everything, but slow to access

- **🔪 RAM (Memory)** → *Kitchen Counter*  
  Only items needed right now — fast but limited space

### Comparison Table

| Feature | Primary Memory (RAM) 🧠 | Secondary Storage 💾 |
|---------|-------------------------|----------------------|
| **Speed** | Super fast (nanoseconds) | Slower (milliseconds) |
| **Volatility** | Volatile | Non-volatile |
| **Capacity** | Low (8–32GB) | High (256GB–2TB+) |
| **Cost** | Expensive per GB | Cheap per GB |
| **CPU Access** | Direct | Must load into RAM first |

---

## 📚 Software Hierarchy

Software acts as the bridge between **user** and **hardware**.

### Two Main Types

**🖥️ System Software** – OS manages hardware (Windows, macOS, Linux)

**📱 Application Software** – User programs (Chrome, Word, VS Code)

### How Software Talks to Hardware

```
           👤 USER (You)
                │
                ▼
      ┌─────────────────┐
      │  📱 Application │  (e.g., Playing a Video Game)
      └─────────────────┘
                │
                ▼
      ┌─────────────────┐
      │ 🖥️ Operating    │  (e.g., Windows 11)
      │    System       │
      └─────────────────┘
                │
                ▼
      ┌─────────────────┐
      │ 🔌 Device       │  (The "Translator" for specific hardware)
      │    Driver       │
      └─────────────────┘
                │
                ▼
      ┌─────────────────┐
      │ ⚙️ HARDWARE     │  (Graphics Card / CPU)
      └─────────────────┘
```

---

## ✍️ Practice Questions (Exam Prep)

### ❓ Q1: Why does a computer need RAM if it has a big Hard Drive?

**Answer:**  
Although Hard Drives provide enough space for permanent storage, they are far too slow for the CPU's processing needs. The CPU requires data to be delivered at lightning speed to function efficiently, which only RAM (Random Access Memory) can provide. Therefore, the computer loads active programs from the slow Hard Drive into the fast RAM so the CPU can access them instantly.

---

### ❓ Q2: Categorize the following

**Items:** Monitor, CPU, Keyboard, Hard Drive, Mouse, Printer

**Answer:**

- **⌨️ Input:** Keyboard, Mouse
- **⚙️ Process:** CPU
- **🖥️ Output:** Monitor, Printer
- **💾 Storage:** Hard Drive

---

### ❓ Q3: Explain the function of the ALU

**Answer:**  
The Arithmetic Logic Unit (ALU) serves as the CPU's calculation engine. It is responsible for executing all mathematical computations (such as addition, subtraction, multiplication, and division) as well as logical operations (such as comparing values to determine true/false outcomes).

---

## 📝 Key Terms

| Term | Definition |
|------|------------|
| **⚡ Volatile** | Memory that loses data when power is off (RAM) |
| **🔒 Non-Volatile** | Storage that retains data without power (HDD/SSD) |
| **⌨️ Input Devices** | Keyboard, Mouse |
| **🖥️ Output Devices** | Monitor, Printer |
| **🧠 CPU** | Brain of the computer |
| **🔄 IPO Cycle** | Input → Process → Output |
| **🖥️ System Software** | Operating System |
| **📱 Application Software** | User programs |

---

**💪 Study Tip:** Focus on understanding the relationships between components rather than just memorizing definitions. Practice explaining concepts using analogies!
---

## 🙋‍♂️ Author  

**Sadid Ahmed** (`litch07`)
