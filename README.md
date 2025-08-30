# NestJS Kafka Typescript Docker

## 📌 Introduction
Backend Project ที่พัฒนาโดยใช้ **NestJS (TypeScript)**  
เพื่อทดสอบการทำงานร่วมกับ **Kafka Message Queue** และ **Docker/Docker Compose**  

Repository นี้ทำหน้าที่เป็น **ตัวกลาง (Root Project)** และใช้ **Git Submodules**  
ในการเชื่อมกับ **Microservices อื่น ๆ** บน GitHub (เช่น Producer และ Consumer Service)

---

## ⚙️ Tech Stack
- **NestJS (TypeScript)** – Backend Framework
- **Kafka** – Message Queue สำหรับ Event-driven Architecture
- **Docker & Docker Compose** – Containerization & Local Orchestration
- **Git Submodules** – เชื่อมต่อกับ Microservices อื่น ๆ

---

## 📂 Repository Structure
- `NestJS-Kafka-Microservice-Producer/` → Producer Service (ส่งข้อความเข้า Kafka Topic)  
- `NestJS-Kafka-Microservice-Consumer/` → Consumer Service (ดึงข้อความจาก Kafka Topic)  
- `kafka-docker/` → Environment Setup สำหรับ Kafka ด้วย Docker Compose  

---

## 🚀 Features
- **Message Producer** → ส่งข้อความเข้าสู่ Kafka Topic  
- **Message Consumer** → ดึงข้อความจาก Kafka Topic และประมวลผล  
- **Containerized Environment** → รัน Kafka, Producer, Consumer ได้ครบชุดด้วย Docker  
- **Modular Microservices** → เชื่อมต่อผ่าน Git Submodules ทำให้ขยายและแยกการพัฒนาได้ง่าย  

---
