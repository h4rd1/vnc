service   /etc/systemd/system 



firewall-cmd --permanent --zone=public --add-port=5901/tcp
firewall-cmd --reload




tigetvnc-server


yum/dnf install tigetvnc -y
yum/dnf install tigetvnc-server -y

vncconfig.sh

