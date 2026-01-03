# nestjs-journey

## راهنمای سریع

### دستور اجرای پروژه

```bash
npm install
npm run start:dev
```

### پورت برنامه

پورت پیش‌فرض `3000` است. اگر متغیر محیطی `PORT` مقداردهی شود، همان مقدار استفاده می‌شود.

### Endpoints

- `GET /health`

تست با curl:

```bash
curl http://localhost:3000/health
```

تست با Postman:

- Method: `GET`
- URL: `http://localhost:3000/health`

نمونه خروجی:

```json
{
  "status": "ok"
}
```

### لینک فایل‌های کلیدی

- [src/app.controller.ts](src/app.controller.ts)
- [src/main.ts](src/main.ts)
