# 🍽️ Kin A Rai Dee MFU

A web application designed to help users discover restaurants in front of Mae Fah Luang University (MFU). The system features restaurant search, rankings, reviews, favorite lists, and management tools for restaurant owners and administrators.

---

## 📌 Project Status

**Status: Rebuilding the project from scratch**  
→ The previous structure is being reworked to improve clarity, usability, and maintainability.

---

## 📖 Table of Contents

- [Introduction](#introduction)
- [Business Objective](#business-objective)
- [Core Features](#core-features)
- [User Roles](#user-roles)
- [Functional Requirements](#functional-requirements)
- [Non-functional Requirements](#non-functional-requirements)
- [User Interface Pages](#user-interface-pages)
- [Database Schema Overview](#database-schema-overview)

---

## 🧩 Introduction

Many new students and visitors are unfamiliar with the restaurants near MFU. This application provides a centralized platform for exploring local eateries with details, ratings, and user reviews.

---

## 🎯 Business Objective

- Display detailed restaurant data including menu, pricing, and location.
- Provide user-generated restaurant reviews and ranking.
- Accessible 24/7 with a UI that’s friendly for first-time users.
- Allow owners to manage their restaurants and menus.
- Support communication between users and admins.

---

## ✨ Core Features

- Browse and search restaurants around MFU
- Filter restaurants by categories
- Rate and review restaurants
- View restaurant location on Google Maps
- Save favorite restaurants
- Restaurant ranking system
- Admin approval system for new restaurant entries
- Contact admin for issues or suggestions

---

## 👥 User Roles

### **User**
- Browse restaurants without login
- Create account with Gmail to review or rate
- Add favorites and manage personal profile

### **Restaurant Owner**
- Register and manage up to 3 restaurants
- Add or delete menus
- Reply to user comments

### **Admin**
- Approve or reject new restaurant entries
- Resolve user-reported issues
- Manage users and restaurant owners

---

## ✅ Functional Requirements (FR Highlights)

| ID   | Feature                              | Role                 |
|------|--------------------------------------|----------------------|
| FR01 | Login                                | All                  |
| FR02 | Sign Up                              | User, Owner          |
| FR03 | Restaurant Searching                 | All                  |
| FR04 | Favorite Restaurants                 | User                 |
| FR05 | Rate and Review                      | User                 |
| FR06 | Ranking                              | User                 |
| FR07 | Account Management                   | User                 |
| FR08 | Restaurant Management                | Owner, Admin         |
| FR09 | Contact Admin                        | User, Admin          |
| FR10 | Reply to Comments                    | Restaurant Owner     |
| FR11 | Restaurant Approval                  | Admin                |
| FR12 | Problem Management                   | Admin                |
| FR13 | Logout                               | All                  |

---

## 🚦 Non-functional Requirements

- **Security**: User passwords are encrypted
- **Usability**: UI designed with accessibility and clarity in mind
- **Reliability**: Minimize system errors and ensure high availability

---

## 🖥️ User Interface Pages

- **Main Page**: Browse, search, view rankings
- **Login / Sign Up Page**: User registration via Gmail
- **Restaurant Search**: Filter by name or category
- **Restaurant Details**: View menu, ratings, and reviews
- **Manage Restaurants**: Add/edit/delete menu items
- **Reply to Comments**: Owners respond to user reviews
- **Favorites Page**: View saved favorite restaurants
- **Admin Dashboard**: Approve requests, solve problems

---

## 🗃️ Database Schema Overview

- **User**: `user_id`, `user_email`, `user_password`, etc.
- **Restaurant Owner**: `restOwner_id`, `rest_id`, etc.
- **Restaurant**: `rest_id`, `menu_id`, `rate`, `location`, etc.
- **Menu**: `menu_id`, `menu_name`, `price`, etc.
- **Review**: `review_id`, `rate`, `user_id`, etc.
- **Admin**: `admin_id`, `rest_id`, `review_id`, etc.

---

## 📅 Contributors

- Sorrawit Tanakhwang (6531503080)  
- Kamoporn Silaloi (6531503094)  
- Sofwan Kasa (6531503098)  
- Metasit Chooree (6531503118)  
- Sirita Jaikham (6531503125)  
- Aphichai Nasongkhram (6531503128)

---

## 📝 License

This project is part of a university assignment and not yet released under an open-source license.
