# Server Refresh - Fork

This is a fork of [Titan 2 - Server Refresh](https://github.com/TitanTF/Server-Refresh) by myst.

## Changes:

- **Fixed critical multiple restart bug**: Added cooldown mechanism to prevent servers from restarting 10-15 times when scheduled time arrives
- **Fixed variable assignment bugs**: Corrected WeeklyRestartDay variable handling in OnCvarChanged function  
- **Fixed StringToLower bug**: Applied string conversion to correct variable for weekly restart day
- **Added schedule display command**: New `sm_restart_schedule` admin command shows complete configuration overview

The original plugin had an issue where timers running every second would trigger multiple restarts during the target minute. This fork implements a 61-second cooldown between restart attempts to ensure only one restart occurs per scheduled time.