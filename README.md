# 🌸 AnimeWorld — ASP.NET Core MVC Master-Details CRUD Application  
*A Complete Anime Character Management System with Identity + Image Upload + Pagination + Master–Details CRUD*

---

## 📌 Overview

**AnimeWorld** is a fully-featured ASP.NET Core MVC application designed to manage:

### ✔ Anime Characters  
### ✔ Genres  
### ✔ Anime Names (child list per character)

It includes:

- **Master–Details CRUD** (AnimeCharacter → AnimeNames)  
- **ASP.NET Core Identity Authentication**  
- **Image Uploading & Auto-Delete on Update/Delete**  
- **Server-side Input Validation**  
- **Drop-down list binding for Genres**  
- **Paging using X.PagedList**  
- **Search Filtering**  
- **ViewModels for clean data flow**  

This is a perfect project for students & developers learning real-world ASP.NET Core MVC architecture.

---

## ⭐ Key Features

### 🔐 Authentication
- Secured with **ASP.NET Core Identity**
- Controller is protected using `[Authorize]`
- Only logged-in users can access AnimeCharacters CRUD

### 📁 CRUD Functionality
- Add / Edit / Delete / Details for Anime Characters
- Add multiple AnimeNames under one character
- Edit and delete remove old AnimeNames properly
- Supports child list clearing + re-insert during Edit

### 🖼 Image Upload System
- Supports `.jpg`, `.jpeg`, `.png`, `.gif`
- Validates file extension & maximum size (2MB)
- Saves to `/wwwroot/uploads`
- Auto delete old picture on update
- Auto delete picture on DeleteConfirmed

### 📑 Pagination + Search
- Search by Character Name
- Paginated using **X.PagedList**
- `pageSize = 2` (change anytime)
- Ordered by Character Name

### 📊 Master–Detail Structure
- AnimeCharacter → AnimeNames (one-to-many)
- Genres dropdown (foreign key)

---

## 🧩 Technologies Used

| Technology | Purpose |
|-----------|----------|
| **ASP.NET Core MVC 7** | Web Framework |
| **Entity Framework Core** | ORM |
| **SQL Server** | Database |
| **Identity** | Authentication |
| **X.PagedList** | Pagination |
| **Bootstrap 5** | UI styling |
| **IFormFile** | Image handling |

---

## 📂 Project Structure

