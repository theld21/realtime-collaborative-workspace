# 👑 Real-time Collaborative Workspace

_Learning Project (PoC): Hành trình chuyển đổi từ Laravel/Vue sang Hệ sinh thái Fullstack TypeScript (Next.js + NestJS). Tập trung vào kiến trúc hệ thống, vận hành Docker & CI/CD._

## 🎯 Mục tiêu dự án

Thay vì tạo ra một ứng dụng nhiều tính năng, dự án này tập trung vào:

- **Mastering TypeScript**: Chuyển đổi hoàn toàn tư duy từ PHP/Dynamic sang Static Typing.
- **Infrastructure as Code**: Vận hành toàn bộ bằng Docker & Docker Compose.
- **Real-time System**: Xử lý dữ liệu đồng bộ qua WebSockets (Socket.io).
- **DevOps Workflow**: Tự động hóa quá trình kiểm thử và release với GitHub Actions & CI/CD.

## 🛠 Tech Stack

| Thành phần    | Công nghệ            | Lý do chọn                                                     |
| :------------ | :------------------- | :------------------------------------------------------------- |
| **Frontend**  | Next.js (App Router) | SEO-friendly, Server Components, thống trị React ecosystem.    |
| **Backend**   | NestJS               | Cấu trúc Module/DI chặt chẽ (giống Laravel), chuẩn Enterprise. |
| **Database**  | PostgreSQL + Prisma  | Type-safe ORM cực mạnh cho TypeScript.                         |
| **Real-time** | Socket.io            | Đồng bộ hóa dữ liệu thời gian thực giữa các user.              |
| **DevOps**    | Docker, GH Actions   | Tối ưu hóa vận hành và tự động hóa pipeline.                   |

## 🗓 Lộ trình 20 đêm "Tu luyện" (Progress Tracking)

### Giai đoạn 1: Foundations (The NestJS Way)

- [ ] **Ngày 01**: Setup Docker Compose (Postgres + Adminer). Khởi tạo NestJS project.
- [ ] **Ngày 02**: Thiết kế Database Schema với Prisma. Tạo các bảng Workspace, User.
- [ ] **Ngày 03**: Xây dựng CRUD API cho Workspace (Modules, Controllers, Services).
- [ ] **Ngày 04**: TypeScript Deep Dive: Implement DTOs, Interfaces và Validation Pipes.
- [ ] **Ngày 05**: Refactor Backend theo Repository Pattern & Dependency Injection.

### Giai đoạn 2: The Modern Frontend (Next.js)

- [ ] **Ngày 06**: Khởi tạo Next.js App Router & TailwindCSS.
- [ ] **Ngày 07**: Chuyển đổi từ Vue sang React: Thực hành Hooks (useState, useEffect).
- [ ] **Ngày 08**: Fetching dữ liệu: Server Components vs Client Components (SWR/React Query).
- [ ] **Ngày 09**: Xây dựng giao diện Workspace Editor (UI tương tác cao).
- [ ] **Ngày 10**: Quản lý State tập trung với Zustand (Thay thế cho Vuex/Pinia).

### Giai đoạn 3: Real-time & Logic "Xương cá"

- [ ] **Ngày 11**: Tích hợp Socket.io Gateway trên NestJS.
- [ ] **Ngày 12**: Real-time Cursor: Hiển thị chuột của người dùng khác trong Workspace.
- [ ] **Ngày 13**: Auto-save & Debouncing: Lưu dữ liệu mượt mà không gây nghẽn Server.
- [ ] **Ngày 14**: Xử lý Concurrency: Chuyện gì xảy ra khi 2 người cùng sửa một chỗ?
- [ ] **Ngày 15**: NestJS Guards & Auth: JWT Authentication (So sánh với Laravel Sanctum).

### Giai đoạn 4: Ship it! (DevOps)

- [ ] **Ngày 16**: Viết Dockerfile tối ưu (Multi-stage build).
- [ ] **Ngày 17**: Viết GitHub Actions Workflow: Tự động chạy Lint & Build khi Push.
- [ ] **Ngày 18**: Health Checks & Logging: Giám sát tình trạng ứng dụng.
- [ ] **Ngày 19**: Deploy Backend lên Railway/Fly.io & Frontend lên Vercel.
- [ ] **Ngày 20**: Tổng kết, tối ưu hóa Performance & Viết tài liệu tổng kết bài học.

## 🚀 Cách chạy dự án (Local Development)

**Clone dự án:**

```bash
git clone https://github.com/theld21/realtime-collaborative-workspace.git
```

**Khởi động môi trường (Docker):**

```bash
docker-compose up -d --build
```
