# Directory_Automation

Markdown
# Directory Automation & Cleaner Script

An automated Python script that periodically scans a target directory, identifies empty files (0 bytes), deletes them to save space, and generates detailed tracking logs.

## 🚀 Features
* **Automated Scheduling:** Runs silently in the background and executes the cleanup task every minute.
* **Smart Cleanup:** Safe detection and permanent deletion of zero-byte (empty) files.
* **Dynamic Logging:** Generates unique, time-stamped log files for every run to track execution details and statistics.
* **Robust Verification:** Validates if the path exists and ensures it is a directory before running.

---

## 🛠️ Prerequisites

Before running the script, make sure you have Python installed along with the required `schedule` library.

Install the scheduling dependency via terminal:
```bash
pip install schedule
💻 How to Run
Run the script from your terminal or command prompt by passing the target directory as an argument:

Bash
python 146_DirectoryAutomationEmptyDeleteReportLogTimeStampSchedule.py /path/to/your/directory
Note on Directory Argument
💡 If no directory is specified in the scheduling function, it defaults to tracking a folder named "Marvellous" in the local directory.

📋 Log File Example
Every time the script runs, it creates a log file (e.g., Marvellous_Thu_Jun_18_23_58_00_2026.log) formatted as follows:

Plaintext
------------------------------------------------------------------------------------------
This is a log file created by Marvellous Automation
This is a directory Cleaner Script
------------------------------------------------------------------------------------------
Total files scanned : 142
Total empty files found : 12
This log file is created at : Thu Jun 18 23:58:00 2026
------------------------------------------------------------------------------------------
✍️ Author
Author: Apurva Vilas Shinde

Date: June 18, 2026
