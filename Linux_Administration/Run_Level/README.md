# Run level 

- It defines the operational state of the system.
- It defines the process and daemons run at different run level.
- It is represented using numbers.
- The user can verify the current run level using the command **runlevel**.
- The user can switch between different run levels using **init** command followed by run level number.

## Diffrent run levels and state.

### runlevel 0:
- It is also called as shutdown state.
- No service or daemons run at this run level.
- Switching to this run level leads shutdown of the operating system.
- The can switch to this run level using the command **init 0**.

### runlevel 1:
- It is also called as single user mode.
- Linux won't run any daemons on this level.
- It won't support ssh or remote login.
- The user can use this command to switch to this run level **init 1**.

### runlevel 2:
- It has multi-user support.
- It support ssh but won't support nfs.
- It run some services and daemons
- The user can use this command to switch to this run level **init 2**.

### runlevel 3:
- It run all daemons and services.
- It support remote login through SSH and remote file sharing through NFS.
- It won't support GUI
- The user can switch to this run level using this command **init 3**.

### runlevel 4:
- It is user defined run level and it don't have special features.
- It is identical to run level 3
- The user can switch to this run level using the command **init 4**.

### runlevel 5:
- It is the default run level in linux based operating systems.
- It run all daemons and service.
- It support GUI.
- The user can switch to this run level using the command **init 5**.

### runlevel 6:
- It is also called as restart mode.
- It will restart the operating system if user switch to this run level.
- The user can switch to this run level using the command **init 6**

