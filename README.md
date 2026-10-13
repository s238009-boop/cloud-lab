# 🚀 MERN Stack Application - Lab 04 (Multi-Container with Docker & Cloud Deployment)

Ứng dụng quản lý sinh viên được xây dựng trên kiến trúc **MERN Stack** (MongoDB, Express.js, React.js, Node.js), đóng gói bằng **Docker Containers**, quản lý dịch vụ bằng **Docker Compose** và triển khai thực tế.

---

## 📌 1. Thông Tin Thành Viên / Sinh Viên
- **Họ và tên:** Nguyễn Quốc Vương
- **Mã sinh viên:** 238009
- **Lớp:** DH23TIN10
- **Repository GitHub:** [https://github.com/s238009-boop/mern-demo](https://github.com/s238009-boop/mern-demo)

---

## 🛠 2. Công Nghệ Sử Dụng (Tech Stack)
- **Frontend:** React.js (v2.0)
- **Backend:** Express.js, Node.js (v1.0)
- **Database:** MongoDB Atlas (Cloud Database)
- **Containerization:** Docker, Docker Compose
- **Container Registry:** Docker Hub

---

## 📦 3. Docker Hub Repositories
- **Frontend Image:** [`nguyenquocvuong238009/mern-frontend`](https://hub.docker.com/r/nguyenquocvuong238009/mern-frontend) (Tags: `1.0`, `2.0`)
- **Backend Image:** [`nguyenquocvuong238009/mern-backend`](https://hub.docker.com/r/nguyenquocvuong238009/mern-backend) (Tag: `1.0`)

---

## ⚙️ 4. Hướng Dẫn Chạy Dự Án (Codespaces)

```bash
# Khởi chạy từ Docker Hub Images
docker compose -f docker-compose.hub.yml up -d

# Tắt các services
docker compose -f docker-compose.hub.yml down
