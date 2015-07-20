# try_git

### Configuration

Timeouts are specified in the following format = ```hh:mm:ss.sss``` 

file: ```%SystemDrive%\ProgramData\blahblah\configuration.json```


#### HardwareConfiguration

| Setting | Default | Meaning |
| ------- | ------- | ------- |
| PrinterHardwareType | physical | the type of main board to use <sup>1</sup>|

##### MainBoardConfiguration

| Setting | Default | Meaning |
| ------- | ------- | ------- |
| DataPayloadLength | 54 | the length of the data payload in a main board packet, in bytes |


#### ApplicationConfiguration

| Setting | Default | Meaning |
| ------- | ------- | ------- |
| JsonInitialDirectory | null | managed by the application, do not edit |
| TclInitialDirectory | null | managed by the application, do not edit |
| MaxLogItemsToDisplay | 500 | the maximum number of items to display in  logs <sup>1</sup> |

<sup>1</sup> setting the max number of log items too high can have a negative impact on responsiveness and memory usage.  These logs will be saved to disk, so it is recommended that this setting is kept to 1000 or less, depending on system resources.
