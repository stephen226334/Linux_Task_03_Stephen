# Linux Task 03 – Process Management, System Monitoring & Basic Shell Scripting

## Name

Stephen J

## Date

June 2026

---

# Objective

The purpose of this task is to understand Linux process management, system monitoring, service monitoring, and basic shell scripting using Ubuntu Linux.

---

# Part A – Process Monitoring

## Commands Executed

```bash
ps
ps aux
top
htop
```

## Observations

* Learned how to view running processes.
* Identified Process IDs (PIDs).
* Monitored CPU and memory usage.
* Observed active system processes.

## Screenshots

### Screenshot 01 – ps Command Output

![ps Output](Screenshots/Screenshot_01_ps.png)

### Screenshot 02 – ps aux Command Output

![ps aux Output](Screenshots/Screenshot_02_ps_aux.png)

### Screenshot 03 – top Command Output

![top Output](Screenshots/Screenshot_03_top.png)

### Screenshot 04 – htop Command Output

![htop Output](Screenshots/Screenshot_04_htop.png)

---

# Part B – Process Management

## Commands Executed

```bash
sleep 300
ps aux | grep sleep
kill PID
kill -9 PID
```

## Activities Performed

* Created a temporary process using sleep.
* Located the process PID.
* Terminated the process using kill.
* Forcefully terminated the process using kill -9.

## Screenshots

### Screenshot 05 – Running Sleep Process

![Sleep Process](Screenshots/Screenshot_05_sleep_process.png)

### Screenshot 06 – Finding PID

![Find PID](Screenshots/Screenshot_06_find_pid.png)

### Screenshot 07 – Kill Process

![Kill Process](Screenshots/Screenshot_07_kill_process.png)

### Screenshot 08 – Force Kill Process

![Force Kill](Screenshots/Screenshot_08_force_kill.png)

---

# Part C – System Monitoring

## Commands Executed

```bash
free -h
df -h
uptime
uname -a
```

## Information Collected

* Total RAM
* Available RAM
* Disk Usage
* System Uptime
* Kernel Version

## Files Included

* command_outputs.txt
* system_summary.txt

## Screenshots

### Screenshot 09 – free -h

![free](Screenshots/Screenshot_09_free_h.png)

### Screenshot 10 – df -h

![df](Screenshots/Screenshot_10_df_h.png)

### Screenshot 11 – uptime

![uptime](Screenshots/Screenshot_11_uptime.png)

### Screenshot 12 – uname -a

![uname](Screenshots/Screenshot_12_uname_a.png)

---

# Part D – Service Monitoring

## Commands Executed

```bash
systemctl status ssh
systemctl status NetworkManager
```

## Observations

* Verified service status.
* Checked whether services were active and running.
* Learned the importance of background services.

## Screenshots

### Screenshot 13 – SSH Service Status

![SSH](Screenshots/Screenshot_13_ssh_service.png)

### Screenshot 14 – NetworkManager Service Status

![NetworkManager](Screenshots/Screenshot_14_networkmanager_service.png)

---

# Part E – Shell Scripting

## Script Created

File:

```bash
system_report.sh
```

## Commands Executed

```bash
chmod +x system_report.sh
./system_report.sh
```

## Purpose

The script displays:

* Current User
* Hostname
* Date & Time
* Current Directory
* Memory Usage
* Disk Usage
* System Uptime
* Kernel Version

## Screenshots

### Screenshot 15 – Shell Script Code

![Script Code](Screenshots/Screenshot_15_script_code.png)

### Screenshot 16 – Script Execution Output

![Script Output](Screenshots/Screenshot_16_script_output.png)

---

# Part F – Security Monitoring Challenge

## Commands Researched

```bash
netstat
ss
who
w
last
```

## Files Included

* research_answers.txt

## Screenshots

### Screenshot 17 – netstat

![netstat](Screenshots/Screenshot_17_netstat.png)

### Screenshot 18 – ss

![ss](Screenshots/Screenshot_18_ss.png)

### Screenshot 19 – who

![who](Screenshots/Screenshot_19_who.png)

### Screenshot 20 – w

![w](Screenshots/Screenshot_20_w.png)

### Screenshot 21 – last

![last](Screenshots/Screenshot_21_last.png)

---

# Part G – Mini SOC Activity

Topics Covered:

* Identifying resource-heavy processes.
* Detecting suspicious processes.
* Collecting information before terminating a process.
* Understanding process behavior and system performance.

Research answers are included in:

```text
research_answers.txt
```

---

# Files Included

```text
Linux_Task_03_StephenJ/

├── Screenshots/
├── system_report.sh
├── command_outputs.txt
├── system_summary.txt
├── research_answers.txt
└── README.md
```

---

# Conclusion

This task provided practical experience with Linux process monitoring, process management, service monitoring, system monitoring, shell scripting, and security monitoring techniques. These skills are essential for Linux Administration, System Monitoring, and Cyber Security operations.
