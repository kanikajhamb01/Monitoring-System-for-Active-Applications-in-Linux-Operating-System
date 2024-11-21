# Monitoring-System-for-Active-Applications-in-Linux-Operating-System\

Monitoring system resources and application performance is a crucial task for efficient system management. Existing tools often provide excessive or irrelevant information, making it difficult for users to focus on specific applications. The problem is particularly pronounced for users who wish to track specific metrics for a single application in real-time, such as runtime duration, memory usage, and frequency of usage.
This project aims to address this gap by creating a lightweight, user-friendly Application Monitoring System tailored for Linux-based systems. Using the Linux /proc filesystem, the system will enable users to monitor specific application metrics efficiently.



Functional Requirements
Track Runtime Duration: Calculate how long an application has been running.
Check Memory Usage: Display the memory (RAM) consumed by a specific application.
Log Open Count: Track how many times the application has been opened.
Monitor User Sessions: Provide details of currently logged-in users and their login durations.
Display Memory Statistics: Show total, used, free, and cached memory, along with swap memory details.


Non-Functional Requirements :
Platform Compatibility: The system must run on any Linux distribution (e.g., Ubuntu).
Performance: The application should have minimal overhead and execute tasks efficiently.
Scalability: Ensure compatibility with a variety of Linux processes and applications.
Reliability: Display accurate, real-time data without crashes or errors.
Maintainability: Modular code for easy debugging and future feature expansion.



The Application Monitoring System provides an efficient and user-friendly solution for real-time application monitoring on Linux systems. By leveraging the Linux /proc filesystem and implementing modular functions, the system tracks essential metrics like runtime duration, memory usage, and user sessions with precision. The project serves as a foundation for further enhancements, such as adding a graphical interface or real-time alerts.This project has provided valuable insights into Linux system programming, process management, and resource monitoring, showcasing the power of C programming in solving real-world problems.



