---

# 🚨 Use for Educational Purposes ONLY 🚨  

## 🛠 Maintained Fork of Torshammer  
This is a maintained version of **Torshammer**, updated to work with the latest **TOR port 9150**.  

---

## 📌 Installation  

Clone the repository and navigate to the project folder:  

```bash
git clone https://github.com/Aathithya-Shanmuga-Sundaram/torshammer.git
cd torshammer
```

---

## 🚀 Usage  

Tor’s Hammer provides a terminal-based interface with a built-in help menu to guide you.  

### Example Commands:  

```bash
python torshammer.py -t 192.168.1.100 -r 100000 -T
python3 torshammer.py -t "www.example.com" -r 100000
```

### Parameters:
- **`-t`** → Target IP or domain  
- **`-r`** → Number of requests (higher values increase effectiveness)  
- **`-T`** → Enables TOR for anonymity and bypassing IP bans  

### **Using Tor (`-T` option)**  
If you’re using the `-T` option to route traffic through Tor, ensure Tor is running before executing Torshammer:  

```bash
service tor start
```

### **Fixing "Too many open files" Error**  
If you encounter the following error:  

```bash
OSError: [Errno 24] Too many open files
```  

Increase the file descriptor limit before running Torshammer:  

```bash
ulimit -n 65535
```

---

## 🔥 Key Features  
✔ **Supports TOR** (`-T` flag) for increased security and anonymity  
✔ **Highly effective** against **Apache servers** (but not against Nginx)  
✔ **Multi-threaded attack** to increase impact  

⚠ **Disclaimer:** Use responsibly. This tool is for educational and research purposes only.  

📅 **Last used on:** *17/03/2025*  
