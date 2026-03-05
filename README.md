# 🎓 Exam Seating Plan Generator Pro

> A smart, beautiful, and completely browser-based tool to automatically arrange exam seating with maximum physical distance. Zero backend required!

## 📑 Table of Contents

* [✨ Features](#-features)
* [🚀 Getting Started](#-getting-started)
* [💡 How to Use](#-how-to-use)
* [📂 Excel Data Format](#-excel-data-format)
* [🛠️ Built With](#%EF%B8%8F-built-with)

## ✨ Features

* **🧠 Smart Distance Algorithm:** Automatically distributes students using a "Checkerboard" pattern. If there are extra seats, it maximizes physical distance. It strictly prevents students from the same batch from sitting next to each other!
* **📊 Full Excel Integration:** Powered by `SheetJS`. Download templates, import your university data, and export your complete setups directly to `.xlsx`.
* **🖨️ Professional Print Engine:** Generates a flawless A4 print layout. Features formal headers for every page and automatic page breaks for different examination rooms.
* **🚫 Collision Detection:** Clearly warns you if the student count exceeds your total room capacity, highlighting exactly which roll numbers couldn't be seated.
* **💾 State Management:** Export your active session to Excel and load it back anytime to resume exactly where you left off.

## 🚀 Getting Started

Because this tool is entirely browser-based, there is **zero installation** required!

### Prerequisites

All you need is a modern web browser:
* Google Chrome
* Apple Safari
* Mozilla Firefox
* Microsoft Edge

### Run Locally

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/exam-seating-plan-pro.git](https://github.com/yourusername/exam-seating-plan-pro.git)
