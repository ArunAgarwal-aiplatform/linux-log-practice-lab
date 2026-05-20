# 🐧 Linux Log Practice Lab

This is my first small Linux practice project.  
I made it while learning **Linux basics** and starting with **log analysis / ELK**.

The goal of this project was simply to practice common Linux commands on sample log files and get comfortable working inside the terminal.

---

## ⚙️ What This Project Does

- Reads sample web and auth logs
- Finds **HTTP 5xx errors**
- Finds failed **SSH login attempts**
- Counts top IP addresses
- Counts HTTP status codes
- Checks running processes and open ports
- Practices file operations and permissions

---

## 📁 Files Included

- `access.log` → sample web access log  
- `auth.log` → sample auth log  
- `analyze.sh` → main bash script  
- `.gitignore` → ignores generated files  

---

## 🛠️ Commands Used

`grep` • `awk` • `sort` • `uniq` • `chmod` • `find` • `ps` • `ss` • `mkdir` • `cp`

---

## ▶️ How to Run

```bash
chmod +x analyze.sh
./analyze.sh
```

---

## 📂 Output

Results are generated inside:

```bash
project_work/output/
```

Example output files:

```bash
http_errors.log
failed_login.log
top_ips.txt
status_codes.txt
open_ports.txt
process_list.txt
```

---

## 📚 What I Learned

This project helped me practice:

- basic bash scripting
- log filtering and text processing
- Linux permissions
- pipes and command chaining
- simple system and network checks

I kept the project simple on purpose since this is one of my first Linux projects 🚀