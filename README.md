### 关闭防火墙
chkconfig iptables on

chkconfig iptables off

### 关闭SELinux
vim /etc/selinux/config  改为 SELINUX=disabled

init 6

### smb 开机启动
vi /etc/rc.d/rc.local
/etc/rc.d/init.d/smb start

### 添加smbpasswd
smbpasswd -a cliff
