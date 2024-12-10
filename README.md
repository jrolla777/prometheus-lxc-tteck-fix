The consoles and consoles_library folders were removed from recent Prometheus releases, breaking tteck's script: <br>
https://github.com/tteck/Proxmox/blob/main/ct/prometheus.sh <br>
Line 69: cp -rf consoles/ console_libraries/ /etc/prometheus/ <br>
<br><br>
Run to install:<br>
# bash -c "$(wget -qLO - [https://github.com/tteck/Proxmox/raw/main/ct/prometheus.sh](https://github.com/jrolla777/prometheus-lxc-tteck-fix/raw/main/prometheus_fix.sh))"
