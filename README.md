# 💳 Expense Tracker App

> A cross-platform personal finance manager built with **Flutter** and **Material 3**, featuring dynamic bar chart analytics, adaptive layouts, and seamless Light/Dark theme support.

---

## 📸 Screenshots

| Light Theme | Dark Theme / Landscape | Input Modal |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8e98de56-4230-47fb-9521-d8d436bb2d83" width="260" alt="Expense List - Light Mode" /> | <img src="https://github.com/user-attachments/assets/9340ffbd-91b5-459a-a0a4-c8c4957e5602" width="400" alt="Landscape Chart View" /> | <img src="https://github.com/user-attachments/assets/d677c011-6ada-415b-b54f-75cb5db438f0" width="220" alt="New Expense Modal" /> |

---

## 📌 Overview

**EXP_Tracker_App** is an intuitive expense management tool designed to give users clear visibility into their spending habits. It combines reactive state handling with custom chart rendering to categorize expenses and display dynamic spending breakdowns across multiple platforms.

---

## 🎯 Key Features

* **Full CRUD Support:** Add, review, and dismiss individual expense records on the fly.
* **Dynamic Chart Visualization:** Real-time bar charts that calculate and display category-based spending proportions.
* **Adaptive & Responsive UI:** Automatically adjusts between portrait and landscape orientations across screen sizes.
* **Theme Support:** Fully customized Material 3 color schemes for both Light and Dark modes.
* **Multi-Platform Ready:** Native performance across Android, iOS, macOS, and Web.

---

## 🛠 Tech Stack & Architecture

* **Framework:** [Flutter](https://flutter.dev/) (Material 3 UI Toolkit)
* **Language:** [Dart](https://dart.dev/)
* **State Management:** Stateful Widgets & dynamic list filtering
* **Key Components:**
  * Modal bottom sheets for intuitive entry logging
  * Dismissible swipe-to-delete interactions with undo actions
  * Custom bar widgets with normalized height scaling

---

## 📦 Project Structure

```text
EXP_Tracker_App/
│
├── chart.dart            # Chart wrapper and category calculation
├── chart_bar.dart        # Custom dynamic vertical bar component
├── expense.dart          # Data model, category enums, and formatters
├── expenses.dart         # Main stateful view and screen scaffold
├── expenses_items.dart   # Individual expense card presentation
├── expenses_list.dart    # Scrollable list and dismissible handling
├── new_expense.dart      # Modal bottom sheet for logging new expenses
├── main.dart             # App entry, color scheme, and theme configs
├── .gitignore            # Git configuration
└── README.md             # Project documentation
