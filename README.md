# Cloud Computing Laboratory (CS4V51) - Lab Manual & Experiments

This repository contains the complete set of practical experiments for the **CS4V51: Cloud Computing Laboratory** course, formatted with structured step-by-step instructions (`input.txt`) and expected terminal/GUI outputs (`output.txt`) for each experiment.

---

## 📂 Repository & Directory Structure

```
CC Lab/
├── README.md
├── Ex01_Virtual_Workstation/
│   ├── input.txt
│   └── output.txt
├── Ex02_Virtual_Machine_C_Compiler/
│   ├── input.txt
│   └── output.txt
├── Ex03_Google_App_Engine_HelloWorld/
│   ├── input.txt
│   └── output.txt
├── Ex04_GAE_Launcher_Web_Applications/
│   ├── input.txt
│   └── output.txt
├── Ex05_CloudSim_Simulation/
│   ├── input.txt
│   └── output.txt
├── Ex06_VM_File_Transfer_Procedure/
│   ├── input.txt
│   └── output.txt
├── Ex07_Hadoop_Single_Node_Cluster_WordCount/
│   ├── input.txt
│   └── output.txt
├── Ex08_Docker_First_Container/
│   ├── input.txt
│   └── output.txt
└── Ex09_Run_Container_From_Docker_Hub/
    ├── input.txt
    └── output.txt
```

---

## 📋 Experiment Index & Syllabus Overview

| Ex. No | Experiment Title | Directory | Key Tools & Technologies |
| :---: | :--- | :--- | :--- |
| **01** | [Virtual Workstation Setup](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex01_Virtual_Workstation) | [`Ex01_Virtual_Workstation`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex01_Virtual_Workstation) | Oracle VM VirtualBox, Windows 98 / Linux ISO |
| **02** | [C Compiler in VM & Program Execution](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex02_Virtual_Machine_C_Compiler) | [`Ex02_Virtual_Machine_C_Compiler`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex02_Virtual_Machine_C_Compiler) | TinyCore Linux / CorePlus, GCC (`compiletc`), C |
| **03** | [Google App Engine - Hello World Web App](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex03_Google_App_Engine_HelloWorld) | [`Ex03_Google_App_Engine_HelloWorld`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex03_Google_App_Engine_HelloWorld) | Eclipse IDE, Google Plugin for Eclipse (GPE), GAE Java SDK |
| **04** | [GAE Launcher & Web App Deployment](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex04_GAE_Launcher_Web_Applications) | [`Ex04_GAE_Launcher_Web_Applications`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex04_GAE_Launcher_Web_Applications) | Google Cloud SDK (`gcloud`), Python 2.7 runtime, HTML/CSS |
| **05** | [Cloud Scenario Simulation using CloudSim](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex05_CloudSim_Simulation) | [`Ex05_CloudSim_Simulation`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex05_CloudSim_Simulation) | CloudSim 3.0.3, Apache Commons Math 3.6.1, Eclipse IDE |
| **06** | [VM-to-VM & Host-to-Guest File Transfer](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex06_VM_File_Transfer_Procedure) | [`Ex06_VM_File_Transfer_Procedure`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex06_VM_File_Transfer_Procedure) | VirtualBox Guest Additions, Shared Folders, USB, SCP |
| **07** | [Hadoop Single Node Cluster & WordCount](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex07_Hadoop_Single_Node_Cluster_WordCount) | [`Ex07_Hadoop_Single_Node_Cluster_WordCount`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex07_Hadoop_Single_Node_Cluster_WordCount) | Apache Hadoop 2.7.0, OpenJDK 7, HDFS, YARN, MapReduce |
| **08** | [First Container Creation using Docker](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex08_Docker_First_Container) | [`Ex08_Docker_First_Container`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex08_Docker_First_Container) | Docker Engine, Dockerfile, Python 3 image |
| **09** | [Run Containers from Docker Hub](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex09_Run_Container_From_Docker_Hub) | [`Ex09_Run_Container_From_Docker_Hub`](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex09_Run_Container_From_Docker_Hub) | Docker Hub, Ubuntu, Nginx, MongoDB, CLI exec/prune |

---

## 📖 Detailed Experiment Summaries

### 🔹 [Ex 01: Virtual Workstation](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex01_Virtual_Workstation)
- **Aim**: Install VirtualBox/VMware/equivalent open source cloud workstation with different flavours of Linux or Windows OS on top of Windows 8 and above.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex01_Virtual_Workstation/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex01_Virtual_Workstation/output.txt)
- **Summary**: Download and install Oracle VM VirtualBox 7.x on Windows host machine, create a new VM with allocated RAM/vCPU/Storage, mount an OS installation media (Windows 98/Linux), and successfully boot into the guest operating system desktop.

### 🔹 [Ex 02: Virtual Machine – C Compiler](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex02_Virtual_Machine_C_Compiler)
- **Aim**: Install a C compiler in the virtual machine created using VirtualBox and execute simple C programs.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex02_Virtual_Machine_C_Compiler/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex02_Virtual_Machine_C_Compiler/output.txt)
- **Summary**: Boot TinyCore Linux/CorePlus in VM, use `tce-load -wi compiletc` to install GCC development tools, write a leap year evaluation C program, compile using `cc demo.c`, and run `./a.out`.

### 🔹 [Ex 03: Install Google App Engine & Hello World Web App](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex03_Google_App_Engine_HelloWorld)
- **Aim**: Install Google App Engine. Create a Hello World app and other simple web applications using Python/Java.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex03_Google_App_Engine_HelloWorld/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex03_Google_App_Engine_HelloWorld/output.txt)
- **Summary**: Configure Eclipse IDE with Google Plugin for Eclipse (GPE) and GAE Java SDK, create a new Web Application Project (`HelloWorld`), configure `appengine-web.xml`, test locally on `http://localhost:8888/`, and deploy to Google App Engine (`http://<app-id>.appspot.com/`).

### 🔹 [Ex 04: Use GAE Launcher to Launch Web Applications](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex04_GAE_Launcher_Web_Applications)
- **Aim**: Use GAE launcher / Google Cloud SDK to launch web applications.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex04_GAE_Launcher_Web_Applications/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex04_GAE_Launcher_Web_Applications/output.txt)
- **Summary**: Structure static website assets (`app.yaml`, `www/index.html`, `css/style.css`), define handler routing rules in `app.yaml`, deploy via `gcloud app deploy`, and launch browser using `gcloud app browse`.

### 🔹 [Ex 05: Simulate a Cloud Scenario Using CloudSim](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex05_CloudSim_Simulation)
- **Aim**: Simulate a cloud scenario using CloudSim and run a scheduling algorithm that is not present in CloudSim.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex05_CloudSim_Simulation/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex05_CloudSim_Simulation/output.txt)
- **Summary**: Import CloudSim 3.0.3 source code into Eclipse IDE as a Java project, link Apache Commons Math 3.6.1 external JAR to build path, run `CloudSimExample1.java` simulation, and evaluate Datacenter, VM, and Cloudlet scheduling execution metrics.

### 🔹 [Ex 06: Procedure to Transfer Files Between Virtual Machines](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex06_VM_File_Transfer_Procedure)
- **Aim**: Find a procedure to transfer files from one virtual machine to another virtual machine (and host-guest).
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex06_VM_File_Transfer_Procedure/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex06_VM_File_Transfer_Procedure/output.txt)
- **Summary**: Implement and test multiple VM file transfer mechanisms: (1) Bidirectional Drag-and-Drop / Shared Clipboard, (2) USB Controller Passthrough via VirtualBox Extension Pack, (3) Permanent Auto-Mounted Shared Folders via Guest Additions, and (4) Network Transfer via SCP.

### 🔹 [Ex 07: Install Hadoop Single Node Cluster & Run WordCount](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex07_Hadoop_Single_Node_Cluster_WordCount)
- **Aim**: Install Hadoop single node cluster and run simple applications like WordCount.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex07_Hadoop_Single_Node_Cluster_WordCount/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex07_Hadoop_Single_Node_Cluster_WordCount/output.txt)
- **Summary**: Configure Java 7, passwordless SSH keys, dedicated `hadoop` user, extract Apache Hadoop 2.7.0, configure XML configs (`core-site.xml`, `hdfs-site.xml`, `yarn-site.xml`, `mapred-site.xml`), format HDFS NameNode, start HDFS/YARN daemons, write Java MapReduce `WordCount.java`, build JAR, and execute job over HDFS dataset.

### 🔹 [Ex 08: Creating and Executing Your First Container Using Docker](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex08_Docker_First_Container)
- **Aim**: Write a program to create and execute your first container using Docker.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex08_Docker_First_Container/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex08_Docker_First_Container/output.txt)
- **Summary**: Install Docker Engine, create a project with `main.py` (`print("Docker is magic!")`) and a custom `Dockerfile` (`FROM python:latest`, `COPY main.py /`, `CMD ["python", "./main.py"]`), build image `docker build -t python-test .`, execute container, and manage images/containers.

### 🔹 [Ex 09: Run a Container from Docker Hub](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex09_Run_Container_From_Docker_Hub)
- **Aim**: Write a program to run a container from Docker Hub.
- **Files**: [input.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex09_Run_Container_From_Docker_Hub/input.txt) | [output.txt](file:///c:/Users/Admin/Desktop/CC%20Lab/Ex09_Run_Container_From_Docker_Hub/output.txt)
- **Summary**: Pull and run interactive Ubuntu container with `top`, inspect namespace via `docker container exec -it <id> bash` and `ps -ef`, run detached multi-service containers (Nginx on port 8080 and MongoDB on port 8081), verify HTTP responses, and clean up system resources with `docker system prune`.

---
*Created as part of the CS4V51 Cloud Computing Lab Coursework.*
