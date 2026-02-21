# Desktop Calculator - C# / WinForms

A lightweight, clean desktop calculator built with **C#** and **Windows Forms**. This project was a personal challenge to step away from web development and dive into the **.NET ecosystem** to practice object-oriented logic and event-driven programming.

## 🛠 Tech Stack
* **Language:** C#
* **Framework:** .NET 7.0 (WinForms)
* **Environment:** Developed for Windows (Visual Studio)

## ☑️ Features
* **Custom UI:** I manually designed the interface, including color-coded buttons (Orange for action, Red for clear) for a better user experience.
* **Math Engine:** Implemented a robust `switch-case` logic to handle basic operations: addition, subtraction, multiplication, and division.
* **State Management:** The app correctly handles decimal-like behavior, clearing states, and sequential calculations.

## 🚀 How to Run the Project (Important!)

To avoid common errors, please follow these instructions carefully.

### 1. Prerequisites
* **Visual Studio 2022:** Download the free [Community Edition](https://visualstudio.microsoft.com/vs/community/).
* **Workload:** During installation, you **MUST** check the box: **".NET desktop development"**.
* **Essential Runtime:** This project requires **.NET 7.0**. If it's not installed, the app won't run. 
  * You can download it manually here: [.NET 7.0 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/7.0) (Choose "Download x64" under "Desktop Runtime").

### 2. How to Open Properly
**Do not run the project directly from the ZIP folder!**
1. Download the repository and **Extract All** files to a folder on your computer (e.g., Desktop).
2. Go to the project folder.
3. **Important:** Open the file named **`Calculator.csproj`**. 
   * *Tip:* If you open `Calculator_Project.sln` and see a "Project Not Found" error, it means the paths are broken. Just close it and open `Calculator.csproj` instead.

### 3. Launching the App
1. Once Visual Studio loads the project, look at the top-center toolbar.
2. Find the **Green Play Button** (Triangle) labeled **Calculator**.
3. Click it. The calculator window will appear in a few seconds!

---

## 📂 Code Structure
* `Form1.cs` — Contains the core mathematical logic and button click events.
* `Form1.Designer.cs` — Holds the UI layout and component styling.
* `Program.cs` — The main entry point of the application.
