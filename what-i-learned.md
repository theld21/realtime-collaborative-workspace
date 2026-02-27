# Day 1

- Cài đặt docker
  - Docker: Containerization
  - Docker Compose: Multi-container application
  - docker-compose.yml: Define services
  - Dockerfile: Build image

# Day 2

- Cài đặt và tìm hiểu về prisma
  - Prisma: ORM, schema first
  - Cách tạo model
  - Cách chạy migration dev `npx prisma migrate dev` (tạo file migration, có thể reset database)
  - Cách chạy migration production `npx prisma migrate deploy` (đọc các file SQL có sẵn trong thư mục migrations và áp dụng vào DB)
  - Cách generate prisma client `npx prisma generate` (tạo client cho typescript - Type-safety để framework có thể tương tác với database đúng)
