รองรับ
Debian7x64

เว็บ
Digitalocean,Vultr,ZCloud,GoogleCloud,AmazonCloud

คำสั่งติดตั้ง

1. พิมพ์ sudo su
2. พิมพ์ cd && wget https://github.com/byvpn/Debian7x64/raw/master/install && chmod +x install && ./install

--------------------------------------------------------
ติดตั้งระบบเสร็จเรียบร้อยแล้ว
--------------------------------------------------------
เกี่ยวกับผู้พัฒนา
   - โดย : คุณเต้ ทารุมะ (เต้เล็ก)
   - ไอดีลาย : Ns.NeverDie
   - เบอร์โทร : 095-4172543
   - เว็บไซต์ : http://www.byvpn.net
   - เฟชบุ๊คส่วนตัว : https://www.facebook.com/Tae.taruma
--------------------------------------------------------
ข้อมูลเซิร์ฟเวอร์
   - IPv6 : (ปิดใช้งาน)
   - Fail2Ban : (เปิดใช้งาน)
   - IPTables : (เปิดใช้งาน)
   - AutoReboot : (ปิดใช้งาน)
   - TimeZone : เอเชีย/กรุงเทพฯ (เปิดใช้งาน)
--------------------------------------------------------
ข้อมูลแอพพลิเคชันและพอร์ต
   - IP : $MYIP
   - Nginx : 81
   - BadVPN : 7300
   - OpenVPN : 1194
   - PPTPVPN : 1732
   - OpenSSH : 22,143
   - DropBear : 443,109,110
   - SquidProxy : 80,3128,8000,8080
--------------------------------------------------------
เครื่องมือเสริมในเซิร์ฟเวอร์
   - htop
   - iftop
   - mtr
   - nethogs
   - screenfetch
--------------------------------------------------------
ข้อมูลพรีเมี่ยมสคริปต์เมนู
   - เข้าสู่ระบบเมนูพิมพ์ : menu
--------------------------------------------------------
ข้อมูลสำคัญ
   - Vnstat : http://$MYIP:81/vnstat/
   - MRTG : http://$MYIP:81/mrtg/
   - Webmin http://$MYIP:10000/
   - ConfigOpenVPN http://$MYIP:81/client.ovpn
--------------------------------------------------------
บันทึกการติดตั้ง
   - ดูบันทึกการติดตั้งพิมพ์ : cat /root/log-install.txt
--------------------------------------------------------
