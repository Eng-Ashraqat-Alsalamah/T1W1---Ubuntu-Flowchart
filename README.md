<p align="center">
  <img src="https://s-m.com.sa/ar/images/logo.png" />

<h1 align="center"; color="blue">Ubuntu Flowchart</h1>

<br/>

<br/>

## **Introduction**


<br/>

## **Software Used**
| Component | Function | Picture |
| :---:        |     :---     |          :---: |
| ***Virtual Box***   | ***VirtualBox*** is a virtualization software that allows you to run multiple operating systems (called guests) on a single physical machine (called the host) without the need for separate hardware    | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/VirtualBox_2024_Logo.svg/1200px-VirtualBox_2024_Logo.svg.png" width="200" height="150"/>    |
| ***Ubuntu***    | ***Ubuntu*** is a Linux-based operating system that is user-friendly, open-source, and widely used for Robotics due to its compact memory usage . It is derived from Debian and provides a robust, stable, and secure platform.       | <img src="https://linuxiac.b-cdn.net/wp-content/uploads/2022/03/ubuntu-logo.png" width="350" height="75" />     |

<br/>

## **Terminology**
| Component | Function |
| :---:        |     :---      | 
| ***Shell***   | The interface between the user and the operating system. It interprets and executes user commands     | 
| ***Kernel***    | The core component of an operating system that serves as a bridge between software and hardware. It is responsible for managing system resources, such as CPU, memory, and input/output devices, and ensuring that software applications can run effectively and securely.       | 
| ***Terminal***   | + Displays a command-line interface (CLI) where you can type commands. <br/> + Acts as a bridge between the user and the shell or command interpreter.     | 
| _**Prompt**_    | Executes batch files (.bat) and other Windows-specific commands.       | 
| _**Command Line**_   | Text-based interface where users type commands to interact with the operating system.     | 
| _**Bash**_    | It is a shell language that interprets commands entered by the user and translates them into actions performed by the operating system.       | 
| _**PCI**_   | _**PCI**_ stands for _**Peripheral Component Interconnect**_. It is a hardware interface standard used to connect peripheral devices to a computer's motherboard. PCI allows these devices to communicate with the CPU and other system components.     | 
| _**PWD**_    | _**Print Working Directory**_ shows the absolute path directory you are currently in within the file system.      | 

> [!TIP]
> Understand the terminology table to differentiate and distinquish those terms and its role.

<br/>

## **Flowchart Diagram**
> [!NOTE]
> The Linux Scoring System for permissions are: r = 4, w = 2, and x = 1.
<p align="center" >
 <img width="689" alt="image" src="https://github.com/user-attachments/assets/dedd94a5-72da-493e-9f17-a9cc0aa16448"  />
<img width="767" alt="image" src="https://github.com/user-attachments/assets/da47f635-5d55-4c9c-974d-e5392041793a"  />
</p>

<br/>

## **Methodology**

<br/>

### Code
<p align="center" >
  <ins> <b> Step I </b> </ins>
</p>

```
ash@Ash:~$ ls
```
<img width="950" alt="image" src="https://github.com/user-attachments/assets/0b2a65ba-f184-49dc-bc0a-88d26bf34c35" />

<br/>

<p align="center" >
  <ins> <b> Step II </b> </ins>
</p>

```
ash@Ash:~$ cd Desktop
ash@Ash:~/Desktop$ touch testPermission.py
ash@Ash:~/Desktop$ ls
```
<img width="950" alt="image" src="https://github.com/user-attachments/assets/b785c6fa-f4aa-4b2e-8008-44b43145f5cb" />

<br/>

<p align="center" >
  <ins> <b> Step III </b> </ins>
</p>

```
ash@Ash:~/Desktop$ ls -l
```
<img width="950" alt="image" src="https://github.com/user-attachments/assets/27a9f8e5-e64d-4994-962f-3268741fc31c" />

<br/>

<p align="center" >
  <ins> <b> Step IV </b> </ins>
</p>

```
ash@Ash:~/Desktop$ chmod 775 testPermission.py
```
<img width="950" alt="image" src="https://github.com/user-attachments/assets/e2b22050-487b-4d89-9248-f6d476c5ba05" />


<br/>



## **Conclusion**
> [!TIP]
> The most important thing is to have fun!

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.



## **References**
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: Ref

[^2]: Ref






