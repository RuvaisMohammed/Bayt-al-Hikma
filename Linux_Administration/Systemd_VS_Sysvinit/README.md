# Systemd Vs Sysvinit

## Systemd:
- It uses parallel initialization.
- It uses multiple shell scripts, executes all the shell scripts at a same time.
- stored in rc.d directory

## Sysvinit:
- It uses serial initialization.
- It uses single shell script which contains services and executes one by one.
- Stored in init.d directory
