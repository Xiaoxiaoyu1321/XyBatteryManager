# XyBatteryManager    
### 目的    
为了避免Windows 在低电量时自动睡眠/休眠 时有太多高占用的软件，使得在恢复睡眠/休眠时花费太长的时间，使用这个软件可以在低电量时弹出窗口询问用户是否执行指定的命令行      
### 原理      
调用Windows API 获取当前电池电量，如果电池的电量低于设定的值，将会弹出窗口询问用户是否运行指定的命令，然后逐行使用cmd执行      
