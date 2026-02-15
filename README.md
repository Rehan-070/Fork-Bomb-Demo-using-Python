# ⚠️ Fork Bomb Demo using Python (Educational Purpose Only)

A Python script demonstrating a self-replicating executable behavior using PyInstaller. This project is strictly for educational and cybersecurity awareness purposes.

---

## 🚀 Features

- 🔁 Continuously launches its own executable file
- 🖥️ Runs in console mode
- 📦 Packaged into .exe using PyInstaller
- ⚡ Demonstrates process spawning behavior

---

## 🧠 How It Works

1. The script uses `os.startfile()` to launch its own executable.
2. When converted into `.exe`, it repeatedly opens itself.
3. This creates continuous process spawning.
4. The loop runs indefinitely until system resources are exhausted or manually stopped.

⚠️ This mimics fork bomb–like behavior and can freeze your system.

---

## 🗂️ Project Files

Fork.py  
Fork.spec  

`Fork.py` - Main Python script  
`Fork.spec` - PyInstaller configuration file  

---

## 🛠️ Requirements

Make sure you have **Python 3.x** installed.

Install PyInstaller using:

`pip install pyinstaller`

---

## ▶️ How to Build Executable

# generate spec file (optional)  
`pyinstaller Fork.py`

# build using spec file  
`pyinstaller Fork.spec`

The executable will be generated inside:

`dist/Fork/Fork.exe`

---

## ▶️ How to Run

# run python file  
`python Fork.py`

OR

# run compiled executable  
`Fork.exe`

⚠️ Warning: Running this may freeze your system.

---

## 🧪 Example Behavior

- Program launches its own executable repeatedly.
- Multiple instances appear in Task Manager.
- System may slow down significantly.

---

## 📚 Libraries Used

`os` - File execution handling  
`pyinstaller` - Convert Python script to executable  

---

## 🤝 Contributing

- Fork the repository
- Improve documentation
- Add safety checks
- Add execution limiter
- Create a pull request

---

## 📜 License

This project is for educational purposes only.  
Use responsibly.


---

##  Author
Rehan Shaikh
