### 关闭防火墙
chkconfig iptables on

chkconfig iptables off

### 关闭SELinux
vim /etc/selinux/config  改为 SELINUX=disabled

init 6
