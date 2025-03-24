# Blog Platform

## Overview

This project is a personal blog platform. It features a **NestJS backend** with a **PostgreSQL database** and a **Vue.js 3 frontend**. The platform supports Markdown-based posts, series organization, and infinite scrolling for post browsing.

---

## Technologies

### **Backend**
- **TypeScript**
- **NestJS**
- **TypeORM**
- **PostgreSQL**
- **Swagger**

### **Frontend**
- **TypeScript**
- **Vue.js 3**
- **Vue Router**
- **Markdown-it**
- **Hightligh.js**
- **Tailwind CSS**

---

## Environment Setup

Create a `.env` file for the **backend**.

### Backend (`backend/.env`)

```ini
POSTGRES_HOST=localhost
POSTGRES_PORT=5432
POSTGRES_USER=admin
POSTGRES_PASSWORD=admin
POSTGRES_DB=nestjs

PORT=5000
FRONTEND_URl=http://localhost:5173

JWT_ACCESS_SECRET=your_secret
JWT_ACCESS_EXPIRATION_TIME=1D
JWT_REFRESH_SECRET=your_secret
JWT_REFRESH_EXPIRATION_TIME=30D
```

---

## Installation & Running Locally

### 1️⃣ Clone the Repository

```sh
git clone --recursive https://github.com/aaa-lt/blog.git
cd blog
```

### 2️⃣ Backend Setup

```sh
cd blog-back
npm i
npm run start:dev
```

- Runs the NestJS API on `http://localhost:3000`.

### 3️⃣ Frontend Setup

```sh
cd blog-front
npm i
npm run dev
```

- Runs the Vue.js app on `http://localhost:5173`.

---

## License

This is a personal project and not intended for commercial use.