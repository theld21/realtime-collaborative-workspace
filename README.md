# 👑 Real-time Collaborative Workspace

**`Freaking vibe coding — just me and my keyboard in 2026.`**

Learning Project (PoC): Chuyển đổi stack từ Laravel/Vue sang Next.js/NestJS. TypeScript, System Design, Docker & CI/CD.

## 🎯 Objectives

- **TypeScript Transition**: Chuyển đổi tư duy từ Dynamic sang Static Typing.
- **Infrastructure**: Triển khai hạ tầng với Docker & Docker Compose.
- **Real-time**: Xử lý dữ liệu qua WebSockets (Socket.io).
- **DevOps Workflow**: Tự động hóa Workflow với GitHub Actions & CI/CD.

## 🛠 Tech Stack

| Component     | Technology           |
| :------------ | :------------------- |
| **Frontend**  | Next.js (App Router) |
| **Backend**   | NestJS               |
| **Database**  | PostgreSQL + Prisma  |
| **Real-time** | Socket.io            |
| **DevOps**    | Docker, GH Actions   |

## 🗓 Progress Tracking

~**[_what-i-learned.md_](what-i-learned.md)**

### Phase 1: Foundations (The NestJS Way)

- [x] **Day 01**: Setup Docker Compose (Postgres + Adminer). Khởi tạo NestJS project.
- [x] **Day 02**: Thiết kế Database Schema với Prisma. Tạo các bảng Workspace, User.
- [ ] **Day 03**: Xây dựng CRUD API cho Workspace (Modules, Controllers, Services).
- [ ] **Day 04**: TypeScript Deep Dive: Implement DTOs, Interfaces và Validation Pipes.
- [ ] **Day 05**: Refactor Backend theo Repository Pattern & Dependency Injection.

### Phase 2: The Modern Frontend (Next.js)

- [ ] **Day 06**: Khởi tạo Next.js App Router & TailwindCSS.
- [ ] **Day 07**: Chuyển đổi từ Vue sang React: Thực hành Hooks (useState, useEffect).
- [ ] **Day 08**: Fetching dữ liệu: Server Components vs Client Components (SWR/React Query).
- [ ] **Day 09**: Xây dựng giao diện Workspace Editor (UI tương tác cao).
- [ ] **Day 10**: Quản lý State tập trung với Zustand (Thay thế cho Vuex/Pinia).

### Phase 3: Real-time & Logic "Xương cá"

- [ ] **Day 11**: Tích hợp Socket.io Gateway trên NestJS.
- [ ] **Day 12**: Real-time Cursor: Hiển thị chuột của người dùng khác trong Workspace.
- [ ] **Day 13**: Auto-save & Debouncing: Lưu dữ liệu mượt mà không gây nghẽn Server.
- [ ] **Day 14**: Xử lý Concurrency: Chuyện gì xảy ra khi 2 người cùng sửa một chỗ?
- [ ] **Day 15**: NestJS Guards & Auth: JWT Authentication (So sánh với Laravel Sanctum).

### Phase 4: Ship it! (DevOps)

- [ ] **Day 16**: Viết Dockerfile tối ưu (Multi-stage build).
- [ ] **Day 17**: Viết GitHub Actions Workflow: Tự động chạy Lint & Build khi Push.
- [ ] **Day 18**: Health Checks & Logging: Giám sát tình trạng ứng dụng.
- [ ] **Day 19**: Deploy Backend lên Railway/Fly.io & Frontend lên Vercel.
- [ ] **Day 20**: Tổng kết, tối ưu hóa Performance & Viết tài liệu tổng kết bài học.

## 🚀 Local Development

**Clone project:**

```bash
git clone https://github.com/theld21/realtime-collaborative-workspace.git
```

**Start environment (Docker):**

```bash
docker-compose up -d --build
```
