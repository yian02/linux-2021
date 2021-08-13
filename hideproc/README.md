# hideproc module

This module hides the process from `pidof` or `ps`

## Usage

```shell
# To hide a process
> echo "add <PID1> <PID2> <PID3> ..." | sudo tee /dev/hideproc

# To unhide a process
> echo "del <PID1> <PID2> <PID3> ... " | sudo tee /dev/hideproc
```

## Updates
Update 2021/07/25: Now can accept multiple PIDs as input argument!
