# DeathSide-auto-script-Vpn

OS DEBIAN 7-8-9

OS UBUNTU 14-16-18

wget https://raw.githubusercontent.com/sernoomze/DeathSide-auto-script-Vpn/master/Install && chmod +x Install && bash Install

ลงเสร็จพิมพ์ menu เพื่อใช้งาน


##########################การตั้งค่า webmin############################
ตั้งค่า pass webmin

/usr/share/webmin/changepass.pl /etc/webmin root (ใส่พาสที่ต้องการใช้)

service webmin restart

Exp.

/usr/share/webmin/changepass.pl /etc/webmin root 123456

service webmin restart

ให้เปิดบราวเซอเเล้วพิม http://ไอพีvpsของคุณ:10000
1.ไปที่เมนู Others เเล้วเลือก Perl Modules
2.เลือกช่อง install modules เเล้วเลือก install from cpan
วาง - XML::Parser
3.กด install
