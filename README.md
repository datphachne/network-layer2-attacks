##  Tổng quan đề tài

Đề tài tập trung phân tích và thực nghiệm 5 hình thức tấn công Layer 2 kinh điển trong mạng LAN:
1. **MAC Flooding:** Làm tràn bảng CAM của Switch để chuyển sang chế độ Hub (phát tán gói tin).
2. **ARP Spoofing:** Giả mạo gói tin ARP Reply để nghe lén dữ liệu (Man-in-the-Middle).
3. **DHCP Spoofing:** Giả mạo DHCP Server để cấp phát cấu hình mạng sai lệch cho người dùng.
4. **VLAN Hopping:** Lợi dụng cấu hình Trunk/DTP để nhảy vùng truy cập trái phép phân đoạn mạng khác.
5. **STP Attack:** Giả mạo gói BPDU chiếm quyền Root Bridge nhằm thay đổi cấu trúc cây mạng.

---

##  Mô hình thực nghiệm

* **Nền tảng giả lập:** VMware Workstation, mã nguồn Python (thư viện Scapy).
* **Thiết bị mạng:** Switch Cisco IOU Layer 2.
* **Hệ điều hành đầu cuối:** Ubuntu Linux.
