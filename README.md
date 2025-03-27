# Choreo Go Samples

This repository contains a curated set of **Go-based samples** designed to demonstrate how to build and deploy cloud-native applications and APIs on [Choreo](https://wso2.com/choreo/).

Each sample is a standalone project that can be deployed independently and showcases different Choreo component types, such as Web Applications and APIs.

---

## 📦 Available Samples

### 1. [Glance Web App](https://github.com/manjulaRathnayaka/glance)

**Type:** Web Application  
**Directory:** `glance-web-app/`  
**Description:**  
A Go-powered web app with a clean and minimal interface. This app demonstrates how to serve HTML templates and static files using Go, and how to expose a Web Application in Choreo.

**Highlights:**
- Go `net/http` based server
- HTML templates
- Embedded static content
- Frontend-first use case with optional backend logic

> **Note**: This sample is adapted from the original [Glance repo](https://github.com/manjulaRathnayaka/glance).

---

### 2. Reading List API

**Type:** API  
**Directory:** `reading-list-api/`  
**Description:**  
A simple RESTful API to manage a reading list. It provides endpoints to create, read, update, and delete book entries. This sample demonstrates building and deploying Go APIs in Choreo.

**Highlights:**
- RESTful CRUD operations
- In-memory data storage (can be extended to a DB)
- Designed for easy testing and expansion

---
