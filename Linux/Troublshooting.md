ping - test network connectivity. Example: ping google.com.
nslookup - find IP address for a domain name. Example: nslookup google.com.
traceroute - find the path a packet takes to a destination. Example: traceroute google.com.
df - check disk space usage. Example: df -h.
du - check directory size. Example: du -sh /path/to/directory.
top - display real-time process information. Use q to exit.
htop - similar to top, but with a more user-friendly interface.
lsof - list open files and their associated processes. Example: lsof +D /path/to/directory.
free - check memory usage. Example: free -m.
lspci - list all PCI devices.
lsusb - list all USB devices.
dmesg - display the system message buffer, which includes information about recent system events.
cat /proc/cpuinfo - show information about the system's CPU.
cat /proc/meminfo - show information about the system's memory.
journalctl - view system logs. Example: journalctl -u service-name.
systemctl - control system services. Example: systemctl status service-name.
service - control system services (legacy version, may not be available on all systems). Example: service service-name status.


Notes: service-name should be replaced by name of service youre troubleshooting. 