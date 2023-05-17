# OS_Project

## Group Members
| Name  | Student Id | Email |
| ------------- | ------------- | ------------- |
| MUHAMMAD AHMED  | 21K-3092  | K213092@nu.edu.pk  |
| NIZAMUDDIN | 21K-4744  | K214744@nu.edu.pk  |

## Project Introduction👋

The "Dining Philosopher with System Call" project aims to solve the Dining Philosophers problem using system calls in an operating system environment. By incorporating system calls, we can efficiently manage resources, synchronize processes, and prevent deadlocks and starvation. This project explores the design considerations, data structures, and synchronization mechanisms involved in ensuring fair resource allocation for the philosophers. Through careful analysis and evaluation, we aim to demonstrate the effectiveness and limitations of using system calls in tackling concurrency challenges. Ultimately, this project provides valuable insights into the intricacies of the Dining Philosophers problem while leveraging system calls for optimal solution implementation.


## Project Goal 🔥

The goal of the "Dining Philosopher with System Call" project is to develop a solution that allows philosophers to dine gracefully by avoiding deadlocks and starvation. By incorporating system calls into the implementation, we aim to achieve efficient resource management, synchronization, and process scheduling. The project focuses on designing a system that ensures fair resource allocation, allowing each philosopher to acquire the required forks and proceed with their activities without encountering issues. The ultimate objective is to demonstrate the effectiveness of system calls in addressing concurrency challenges and creating a robust solution for the Dining Philosophers problem.

#### *STEP1* : add the code for dining philosopher and sleep call 
  <details>
  <summary>View ScreenShots</summary>
  
![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/7a4cc832-28a3-4039-bedf-ddb34d52d982)
![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/5c281ef7-a903-4a33-942b-a98d48cdaef7)
</details>

#### *STEP2* make the make file for both system calls there will be used by kernel to create object file for system call
<details>
  <summary>View ScreenShot</summary>
  
![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/708e9102-354f-4485-9ba7-fa47373da790)

![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/09b41e67-2839-4128-983b-28a2e13c3bda)
</details>

#### *STEP3* in the kernel make file add the path to diningphilosophr and sleepcall
<details>
  <summary>View ScreenShots</summary>

![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/0bb6f058-f60c-4169-81d0-0abb34af3993)
</details>

#### *STEP 4* add system call in system table  
<details>
  <summary>View ScreenShots</summary>

 ![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/f0cb621c-2173-4144-8830-27ceca46cc25)
</details>

#### *STEP 5* add Prototype in syscalls.h at the end
<details>
  <summary>View ScreenShots</summary>

![image](https://github.com/MuhammadAhmed3092/OS_Project/assets/125905421/de52e72b-d7dd-447a-a6ec-c7063287a851)
</details>

#### *STEP 6*   installing PREREQUISITIES which can be used in compilation and installation  
<blockquote>
• sudo apt-get install gcc  
• sudo apt-get install libncurses5-dev  
• sudo apt-get install bison  
• sudo apt-get install flex  
• sudo apt install make  
• sudo apt-get install libssl-dev  
• sudo apt-get install libelf-dev  
• sudo apt-get update  
• sudo apt-get upgrade
 </blockquote>

#### *STEP 7* implementing system calls  
<blockquote>
• Make menuconfig to save settings  
• Make -j4   
• Make modules install   
• And in last rebooting the vm  
</blockquote>

