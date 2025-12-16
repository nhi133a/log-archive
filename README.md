## What is log
A log (log file) is a record of activities and events that occur in a system, application, or network while it is running.
## What is a log used for?
- System Monitoring
 + Know if the system is running normally or experiencing errors
 + Monitor CPU, RAM, and services
- Error detection and correction: When an error occurs, check the logs to see when the error happened and which service caused it. This is crucial for debugging.
- Security and Tracking: Logs record: Failed logins, Unauthorized access, Cyberattacks.
 + Logs serve as evidence in case of security incidents.
# log-archive
This program is designed to automate log management on Linux systems, compressing and archiving old logs, deleting outdated logs and backups, thereby optimizing storage space and ensuring system stability.
## Feature
- Interactive log management: Provide a menu of options for the user.
- Allows specifying the log directory.
- Archive old logs
- Compress these log files into a single .tar.gz file.
## Get started
### Step 1
Create file log-archive
```
nano log_archive_interactive.sh
```
change permissions
```
chmod +x
```

```
/var/log/archive/logs_archive_20251215_104437.tar.gz
```
