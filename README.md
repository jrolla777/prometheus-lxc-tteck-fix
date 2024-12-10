The consoles and consoles_library folders were removed from recent Prometheus releases, breaking tteck's script:
https://github.com/tteck/Proxmox/blob/main/ct/prometheus.sh
Line 69: cp -rf consoles/ console_libraries/ /etc/prometheus/
