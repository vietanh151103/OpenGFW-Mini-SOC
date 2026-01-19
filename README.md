# OpenGFW Mini-SOC (Personal Project)

> Dự án cá nhân mô phỏng **Security Operations Center (SOC)** thu nhỏ, tập trung vào **giám sát – phát hiện – phản ứng sự cố an ninh mạng** bằng các công cụ mã nguồn mở.

---

## Giới thiệu

OpenGFW Mini-SOC là một dự án thực hành nhằm:
- Hiểu cách SOC vận hành trong thực tế
- Thực hành tư duy Blue Team / Security Monitoring
- Kết nối Firewall – IDS/IPS – SIEM thành một hệ thống hoàn chỉnh
- Mô phỏng các kịch bản tấn công thật và phản ứng tự động

---

## Mục tiêu

- Phòng thủ nhiều lớp (Defense in Depth)
- Phát hiện tấn công theo thời gian thực
- Phân tích log tập trung
- Tự động chặn IP độc hại
- Phù hợp làm portfolio SOC / Blue Team

---

## Thành phần chính

- **OpenGFW**: Firewall / Gateway
- **Suricata**: IDS/IPS
- **Wazuh**: SIEM
- **Python**: Automation phản ứng sự cố

---

## Kiến trúc tổng thể
[ Attacker (Kali Linux) ]
            |
            v
      [ OpenGFW ]
            |
            v
     [ Suricata IDS/IPS ]
            |
            v
     [ Victim Servers ]
        - Web App
        - Linux Services
            |
            v
        [ Wazuh SIEM ]
        - Log
        - Alert
        - Dashboard

## Kịch bản tấn công

- SQL Injection
- Brute-force
- Port scanning
- DoS / Flood

---

## Công nghệ

| Nhóm | Công cụ |
|---|---|
| Firewall | OpenGFW |
| IDS/IPS | Suricata |
| SIEM | Wazuh |
| Automation | Python |

---

## Kỹ năng đạt được

- SOC workflow
- IDS rule & tuning
- Log analysis
- Incident response
- Automation

---

## ⚠️ Lưu ý

Dự án phục vụ mục đích học tập & nghiên cứu cá nhân.
Không khuyến nghị triển khai trực tiếp trên môi trường production.

