# Linux Troubleshooting Command Cheat Sheet

- `ping`: Test network connectivity. Example: `ping google.com`.
- `nslookup`: Find IP address for a domain name. Example: `nslookup google.com`.
- `traceroute`: Find the path a packet takes to a destination. Example: `traceroute google.com`.
- `df`: Check disk space usage. Example: `df -h`.
- `du`: Check directory size. Example: `du -sh /path/to/directory`.
- `top`: Display real-time process information. Use `q` to exit.
- `htop`: Similar to `top`, but with a more user-friendly interface.
- `lsof`: List open files and their associated processes. Example: `lsof +D /path/to/directory`.
- `free`: Check memory usage. Example: `free -m`.
- `lspci`: List all PCI devices.
- `lsusb`: List all USB devices.
- `dmesg`: Display the system message buffer, which includes information about recent system events.
- `cat /proc/cpuinfo`: Show information about the system's CPU.
- `cat /proc/meminfo`: Show information about the system's memory.
- `journalctl`: View system logs. Example: `journalctl -u service-name`.
- `systemctl`: Control system services. Example: `systemctl status service-name`.
- `service`: Control system services (legacy version, may not be available on all systems). Example: `service service-name status`.


# Notice
 Replace <span style="color:red">`service-name`</span> with the name of the service you're troubleshooting. 
