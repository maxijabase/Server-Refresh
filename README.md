Server Refresh
---
The server refresh module of Titan. All inclusive server restart features in one plugin, ensures your server is always refreshed and prepared for the next load.

### Features
---
- Set an Individual Custom Restart Message for
  - Map Restart
  - Server Restart
  
- Set Restart Map or Server Individually for
  - Empty
  - Every Hour
  - Every Day
  - Every Week
  
- Add a Wait Time before Restarting for (only useful for notifying players about a restart, if player counts are ignored then this is useless)
  - Empty
  - Every Hour
  - Every Day
  - Every Week
  
- Set Ignore Player Counts for
  - Empty
  - Every Hour
  - Every Day
  - Every Week
  
### ConVars
---
Please note that all time ConVars are in string.

| ConVar | Description | Default Value | 0 = | 1 = | Minimum Value | Max Value |
|-----------------------------------|-----------------------------------------------------------------------------------|-------------------------------------------------|-------|--------|---------------|-----------|
| `sm_restart_message` | Change the message that appears before the server is restarted | "The server will be restarting in {0} seconds." |  |  |  |  |
| `sm_restart_map_message` | Change the message that appears before the map is restarted | "The map will be refresh in {0} seconds." |  |  |  |  |
| `sm_restart_empty` | Enable restart when empty | 1 | No | Yes |  |  |
| `sm_restart_empty_wait` | The amount of time to wait after a server is emptied before restarting in seconds | 30 |  |  |  |  |
| `sm_restart_empty_type` | The type of restart when empty | 0 | Map | Server |  |  |
| `sm_restart_hourly` | Enable hourly restart | 1 | No | Yes |  |  |
| `sm_restart_hourly_wait` | The amount of time to wait after an hourly restart is here in seconds | 30 |  |  |  |  |
| `sm_restart_hourly_time` | At what minute should the restart happen in 2 digits | "00" |  |  | 00 | 60 |
| `sm_restart_hourly_type` | The type of restart done hourly | 0 | Map | Server |  |  |
| `sm_restart_hourly_ignoreplayers` | Ignore players on hourly restart | 0 | No | Yes |  |  |
| `sm_restart_daily` | Enable daily restart | 1 | No | Yes |  |  |
| `sm_restart_daily_wait` | The amount of time to wait after an daily restart is here in seconds | 30 |  |  |  |  |
| `sm_restart_daily_time` | At what hour and minute should the restart happen in 4 digits | "0500" |  |  | "0000" | "2359" |
| `sm_restart_daily_type` | The type of restart done daily | 0 | Map | Server |  |  |
| `sm_restart_daily_ignoreplayers` | Ignore players on daily restart | 0 | No | Yes |  |  |
| `sm_restart_weekly` | Enable weekly restart | 0 | No | Yes |  |  |
| `sm_restart_weekly_wait` | The amount of time to wait after an weekly restart is here in seconds | 30 |  |  |  |  |
| `sm_restart_weekly_day` | On which day should the restart happen in 3 letters | "sun" |  |  |  |  |
| `sm_restart_weekly_time` | At what hour and minute should the restart happen in 4 digits | "0500" |  |  | "0000" | "2359" |
| `sm_restart_weekly_type` | The type of restart done weekly | 1 | Map | Server |  |  |
| `sm_restart_weekly_ignoreplayers` | Ignore players on weekly restart | 0 | No | Yes |  |  |
