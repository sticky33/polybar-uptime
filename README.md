# polybar-uptime

A simple script to show the uptime of the device in polybar.

![polybar-uptime](screenshots/1.png)


## Dependencies
* `uptime`

## Module

```ini
[module/session-time]
type = custom/script
exec = ~/polybar-scripts/session.sh
interval = 1

...
```
