# System_monitoring_scrp

System Monitoring Dashboard Script

Overview ---

This script provides a real-time monitoring dashboard for system resources, including CPU, memory, disk usage, network activity, processes, and essential services. It can display the full dashboard or individual components using command-line switches.

Usage
Running the Full Dashboard
To run the full dashboard with automatic refresh:

./system_monitor.sh

Viewing Specific Sections
You can view specific parts of the dashboard by using the following switches:
	
 CPU Usage: ./system_monitor.sh -cpu
	
 Memory Usage: ./system_monitor.sh -memory
	
 Network Monitoring: ./system_monitor.sh -network
	
 Disk Usage: ./system_monitor.sh -disk
	
 System Load: ./system_monitor.sh -load
	
 Process Monitoring: ./system_monitor.sh -processes
	
 Service Monitoring: ./system_monitor.sh -services

Examples
	View top 10 most used applications: ./system_monitor.sh -cpu
	
 Check disk usage: ./system_monitor.sh -disk
 
	Monitor network statistics: ./system_monitor.sh -network

Requirements

•	Bash shell

•	ps, ss, netstat, ifstat, df, free, swapon, mpstat, systemctl installed on the system.


