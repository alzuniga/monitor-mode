# MONITOR MODE
&nbsp;

&nbsp;

## ABOUT:
---
Monitor Mode is a bash script that facilitates toggling a network interface from `managed mode` to `monitor mode`; or from `monitor mode` to `managed mode`.
&nbsp;

&nbsp;

&nbsp;

## REQUIREMENTS:
---
- Sudo/Root Privileges
- Network interface which supports `monitor mode` (*Promiscuous Mode*)
&nbsp;

&nbsp;

&nbsp;

## INSTALLATION:
---
    user@host:$ git clone https://github.com/alzuniga/monitor-mode.git
    user@host:$ cd ./monitor-mode
    user@host:$ sudo chmod 700 monitor-mode
    user@host:$ sudo chown root:root monitor-mode
    user@host:$ sudo mv monitor-mode /usr/local/bin/monitor-mode
&nbsp;

&nbsp;

## USAGE:
---
    sudo monitor-mode [interface] [state]
  
    interface:        wlan0 | wlan2
    state:            on | off
