# Quiz Practice Toolkits (Semester 4)

This repository contains pure HTML/JS quiz toolkits and question databases to support effective preparation for various academic course examinations, including the newly updated Ho Chi Minh Ideology (TTHCM) module.

## 📌 Latest Updates

The Ho Chi Minh Ideology (TTHCM) quiz system has been successfully updated and pushed. The question bank is neatly categorized by chapters (Chapter 2 through Chapter 6) and comes fully integrated with the following interactive study modes:

* **Randomized Comprehensive Practice:** Instantly shuffles the entire question bank across all chapters for an adaptive testing experience.
* **Chapter-Specific Training:** Pick any targeted chapter and choose between two study options:
    * *Randomized Quiz (Instant feedback):* Select your choice and check instant correct/incorrect color indicators along with the textbook reference right under the question.
    * *Sequential Self-Study:* Display all questions as a complete list, then click submit to get graded at the very end.
* **Standardized Exam Simulation:** Randomly extracts exactly 50 questions with a strict 60-minute countdown clock to get you familiar with real-world exam pressure.

---

## 📁 Repository Directory Structure

~~~text
.
├── Ckdt_v1.html
├── Ckdt_V2.html
└── tthcm/
    ├── data.js       # TTHCM Question Bank & Database
    └── index.html     # Interactive Quiz Core Web UI
~~~

---

## 💻 Windows Setup & Execution Guide

To run the TTHCM Quiz application on a Windows machine, you can choose one of the two quick methods below:

### Method 1: Direct Web Download (No Git Installation Required)

1. Navigate to this GitHub repository page on your preferred web browser.
2. Click the green **Code** button at the top right of the page -> Select **Download ZIP**.
3. Once the download finishes, right-click the downloaded ZIP archive and select **Extract All...** to extract it into a standard folder.
4. Open the extracted folder and navigate into the `tthcm/` directory.
5. Double-click the `index.html` file. The Quiz application will instantly boot up inside your default modern web browser (Microsoft Edge, Google Chrome, Brave, etc.).

> [!WARNING]
> **Important Technical Note:** Never separate `index.html` and `data.js` into different folders or rename them. They must always reside together inside the same `tthcm/` folder for the application to pull the database mapping.

---

## 🐧 Linux Clone & Execution Guide

If you are working inside a Linux environment (Ubuntu, Fedora, Arch Linux, Linux Mint, etc.), you can easily clone the repository and run the application using either GUI or CLI:

### 1. Clone the Remote Repository

Open your terminal and clone the codebase using HTTPS or SSH:

* **Using HTTPS protocol:**
~~~bash
git clone https://github.com/TrSonHien/On_tap_ky_3.git
~~~
* **Using SSH protocol (Recommended if SSH Keys are paired):**
~~~bash
git clone git@github.com:TrSonHien/On_tap_ky_3.git
~~~

### 2. Move Into the Target Directory

~~~bash
cd On_tap_ky_3/tthcm
~~~

### 3. Launch the Application

Since this application runs entirely on standard client runtimes (vanilla HTML/JS), you can open it in several ways:

#### 📁 Option A: Using the Graphical User Interface (Easiest)
Simply open your File Manager (Nautilus, Dolphin, Thunar, etc.), navigate to the `On_tap_ky_3/tthcm/` directory, and double-click the `index.html` file. It will automatically load in your system's default browser.

#### 💻 Option B: Using the Universal Terminal Command
To quickly open the app with your default system browser from the terminal without typing specific browser names, use:
~~~bash
xdg-open index.html
~~~

#### 🛠️ Option C: Using Browser-Specific Commands
If you explicitly want to run it on a specific browser, you can use:
* **Firefox:** `firefox index.html &`
* **Google Chrome / Chromium:** `google-chrome index.html &`

---

Best of luck with your revision and ace your upcoming fourth-semester exams!
