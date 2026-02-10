# 🎮 Dino Run Unity

## 1️⃣ Giới thiệu

Game Dino Run là game né chướng ngại vật, người chơi điều khiển khủng long nhảy qua cây xương rồng chạy để ghi điểm.

## 2️⃣ Công cụ

Unity Engine (2D)
C# (lập trình gameplay)
Git & GitHub (quản lý mã nguồn)
Visual Studio Code
ChatGPT – ( AI ChatGPT tạo ảnh)hỗ trợ phân tích logic, debug và định hướng kiến trúc code (bạn đồng hành 🤝)

 ( AI CHATGPT tạo ảnh)

## 3️⃣ Các bước
Bước 1: Tạo Project

Mở Unity Hub

New Project → 2D Core
<img width="1313" height="93" alt="image" src="https://github.com/user-attachments/assets/b8f62246-f547-4d0d-8ed8-b2c7664ed4d9" />


Bước 2: Tạo Nhân Vật

Import sprite khunglong2
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9c106185-1c18-40f8-951d-18c49e0f2230" />


Thêm Rigidbody2D, Collider2D

Viết script điều khiển nhảy
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22a3e048-cf19-45a5-b62a-aa59ffaabe70" />


Bước 3: Tạo Mặt Đất

Thêm Ground
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ad41db7e-60c7-42ed-b78f-3b0989258488" />


Viết script GroundMove

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c7ed674-3b4d-4226-ab9a-be790ba3395b" />


Bước 4: Tạo Chướng Ngại Vật

Tạo Cactus
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f354cd92-e18b-45de-9435-0bd7db834350" />

Viết script CactusMove + Spawner

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/59e33f4c-8de0-4190-b47d-3ad945197ffa" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c11adb89-6162-4e6d-9646-abd70d900336" />


Bước 5: Tính Điểm & Độ Khó



GameManager tăng speed theo thời gian

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/731e3e3a-9109-42b4-b3f2-e5783cbe7b2a" />


Bước 6: Game Over

Khi va chạm → Hiện Game Over

Hiện nút Restart

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/33cb3167-59e2-4c29-b776-e87bfecfb67e" />


4. Kết luận

Game hoàn thành đầy đủ chức năng: chạy, nhảy, tăng độ khó, game over.
