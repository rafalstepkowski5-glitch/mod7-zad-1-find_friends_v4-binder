# Installation and Startup Guide

## Prerequisites
Before getting started, ensure you have the following installed on your system:
- **Python 3.x**
- **pip** (Python package installer)
- **Git** (optional, for version control)

## Installation Guide

### For Linux:
1. **Open a terminal.**
2. **Clone the repository:**  
   ```bash
   git clone https://github.com/USER/REPO_NAME.git
   cd REPO_NAME/mod7-zad-1-find_friends_v4-binder
   ```
3. **Install required packages:**  
   ```bash
   pip install -r requirements.txt
   ```

### For Windows 11:
1. **Open PowerShell or Command Prompt.**
2. **Clone the repository:**  
   ```bash
   git clone https://github.com/USER/REPO_NAME.git
   cd REPO_NAME\mod7-zad-1-find_friends_v4-binder
   ```
3. **Install required packages:**  
   ```bash
   pip install -r requirements.txt
   ```

## Startup Scripts

### Linux:
Create a script named `start.sh`:
```bash
#!/bin/bash
python main.py
```  
Make it executable:
```bash
chmod +x start.sh
```  
Run the script:
```bash
./start.sh
```

### Windows 11:
Create a script named `start.bat`:
```bat
@echo off
python main.py
pause
```  
Run the script by double-clicking `start.bat` in the file explorer.

## Conclusion
You are now set to run the application on both Linux and Windows!