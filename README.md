#วิธีใช้งาน n8n บน GitHub Codespace
![alt text](images/title.png)
```
# ALL STEP
1: กดเปิด Codespace
2: รอ Codespace สร้าง environment
3: รัน n8n ด้วย docker compose
4: เริ่มสร้าง Workflow
```

1: กดเปิด Codespace 
คลิกปุ่ม “<> Code” → เลือกแท็บ “Codespaces”
กดปุ่ม “Create codespace on main”

2: รอ Codespace สร้าง environment
ประมาณ 1-2 นาที ระบบจะทำการติดตั้ง Docker, Docker Compose และ pull container ที่จำเป็นให้คุณอัตโนมัติ

3: รัน n8n ด้วย docker compose
ใน Terminal ให้รันคำสั่งนี้เพื่อเริ่มต้นระบบ:

```
docker compose up
```
จากนั้นคลิก “Ports” → เปิดพอร์ต 5678 (n8n default port) ในเบราว์เซอร์ได้เลย

4: เริ่มสร้าง Workflow
เข้าหน้า UI n8n ได้ที่ลิงก์ของพอร์ตที่เปิดไว้