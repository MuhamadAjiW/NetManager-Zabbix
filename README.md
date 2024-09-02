# NetManager Zabbix
Netmanager Zabbix is an extension to Netmanager used to automate network appliances integration into Zabbix.

### Requirements
This script requires a GNU/Linux environment to execute. Additionally, it also requires:
1. [NetManager](https://github.com/MuhamadAjiW/NetManager) (Ver. 1.0)
2. Curl (Ver. 8.5.0)
3. jq (Ver. 1.7)

### Installation
This script requires placement inside NetManager's extension folder. Allow execution of script using
```
./chmod +x netmgr_zabbix
```

### Usage
This script is cli based, show list of commands using
```
./netmgr_zabbix -h
```

### Notable Features
- Device addition, removal, and status setting
- Template and Host Group ID fetching

## Credits
> [MuhamadAjiW](https://github.com/MuhamadAjiW) <br/>
> [akmaldika](https://github.com/akmaldika)