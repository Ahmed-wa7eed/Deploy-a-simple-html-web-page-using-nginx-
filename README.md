# 🚀 Static Website with Docker & Nginx

This project serves a static website using Docker and the official Nginx image.

---

## 📦 Technologies Used

- **Docker**
- **Nginx**
- **Local Volume Mounting**

## 🐳 How to Run

Use the following command to start the container:

```bash
docker run -it -d --name html -p 8080:80 -v /home/ahmed/website:/usr/share/nginx/html nginx
```
## ✅ Check the Website

To ensure that your website is being served correctly by the Nginx container, follow these steps:

1. Open your web browser.
2. In the address bar, type:
```
http://localhost:8080

```
