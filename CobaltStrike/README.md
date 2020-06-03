# CobaltStrike

<p align="center">
  <img width="600" height="400" src="https://github.com/bigb0sss/RedTeam/blob/master/redteam_logo_top.png">
</p>

## Command References


### Beacons
#### sleep
```css
sleep 60 50                                 ; Sleep 60 sec with 50% of jitter (Call back between 30 to 60 secs randomly) 
```



#### SMB Beacn
```css
spawn <SMB-Listner-Name>                    ; Spawning a peer-to-peer ("P2P") SMB beacon 
inject <PID> <x86|x64> <SMB-Listner-Name>   ; Useful when trying to spawn P2P beacon as different user context
```

#### TCP Beacn
```css
spawn <TCP-Listner-Name>                    ; Spawning a peer-to-peer ("P2P") TCP beacon 
                                            ; TCP beacons can be also run locally by clicking "Bind to localhost only" on GUI
inject <PID> <x86|x64> <TCP-Listner-Name>   ; Useful when trying to spawn P2P beacon as different user context
```