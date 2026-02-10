1. Giới thiệu

Game Dino Run là game né chướng ngại vật, người chơi điều khiển khủng long nhảy qua cây xương rồng để ghi điểm.

2. Công cụ sử dụng

Unity 6

Visual Studio

C#

 ( AI CHATGPT tạo ảnh)

3. Các bước thực hiện
Bước 1: Tạo Project

Mở Unity Hub

New Project → 2D Core
![Step1](docs/images/step1.png)

Bước 2: Tạo Nhân Vật

Import sprite khủng long

Thêm Rigidbody2D, Collider2D

Viết script điều khiển nhảy
![Step2](docs/images/step2.png)
(Chèn ảnh)

Bước 3: Tạo Mặt Đất

Thêm Ground

Viết script GroundMove

![Step3](docs/images/step3.png)

Bước 4: Tạo Chướng Ngại Vật

Tạo Cactus

Viết script CactusMove + Spawner

![Step4](docs/images/step4.png)
Bước 5: Tính Điểm & Độ Khó



GameManager tăng speed theo thời gian

![Step5](docs/images/step5.png)

Bước 6: Game Over

Khi va chạm → Hiện Game Over

Hiện nút Restart

![Step6](docs/images/step6.png)

4. Kết luận

Game hoàn thành đầy đủ chức năng: chạy, nhảy, tăng độ khó, game over.
