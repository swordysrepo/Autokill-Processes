# Autokill-Processes
this is intended to automatically end the processes selected



this utilizes win32 to find and remove processes with python 3.5+

## required libraries
- library
- win10toast
- checkDebug




we run our project using 
```python autokill_processes.py``` 
in command prompt

after setting our parameters in the ```constants.py``` file

# **Usage:*
- find the process you want to end using ```autokill_processes.py --list```
- add this process name to the ```constants.py``` file
- run cmd/anaconda prompt in administrator mode. (when we recieve an error that says the process cannot be ended , the program is not in admin mode)




## **Features:**

- find and list all current processes
- remove the specified processes when they are running
- notifys when a process fails to end


## **options:**

- notifications when a process is ended 
- sound notification when a process is ended


## **upcoming update::**



  - discord notifications with current timestamp of process ended
  - discord notifications of processes running
  - logging all processes running
  - package format
  - cmd commands
  
