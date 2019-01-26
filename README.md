# uptime
Minimal uptime that doesn't require `/proc` and uses `sysinfo`

## Example output
```
$ ./uptime 
Booted on Thursday, January 17 2019, at 10:09:30 AM
Up 1 weeks, 2 days, 6 hours, 2 minutes, and 37 seconds
```

## Motivation
I needed to use it on a system that didn't have `/proc`, was old, and getting
GNU's uptime library depedencies working on the target system wasn't worth the hassle.

