# Filament Shield

A powerful role and permission management system for Laravel Filament applications, built on top of Spatie Permission. It provides a simple and scalable way to implement **Role-Based Access Control (RBAC)** in Filament admin panels.

---

## 🚀 Features

- Role-Based Access Control (RBAC)
- Permission management for Filament resources
- Auto-generate permissions for resources, pages, and widgets
- Integration with Spatie Laravel Permission
- Secure authorization layer for admin panels
- Easy configuration and setup
- Scalable permission architecture
- Works seamlessly with Filament v3/v4

---

## 🛠️ Tech Stack

- Laravel
- Laravel Filament
- Spatie Laravel Permission
- PHP
- MySQL

---

## 📦 Installation

### Step 1: Install via Composer

```bash
composer require bezhansalleh/filament-shield
```

---

### Step 2: Publish Config

```bash
php artisan vendor:publish --tag=filament-shield-config
```

---

### Step 3: Run Migration

```bash
php artisan migrate
```

---

### Step 4: Install Shield

```bash
php artisan shield:install
```

---

## ⚙️ Usage

### Generate Permissions

```bash
php artisan shield:generate
```

This will automatically create permissions for:
- Resources
- Pages
- Widgets

---

### Assign Roles

You can assign roles to users via:

- Filament Admin Panel
- Seeder
- Programmatically via code

---

## 🔐 How It Works

Filament Shield extends Filament’s authorization system by:

- Mapping permissions to resources
- Controlling access at action level
- Restricting UI visibility based on roles
- Ensuring secure admin operations

---

## 🎯 Purpose

This package is designed to simplify the implementation of **secure and scalable access control** in Filament applications without writing repetitive authorization logic.

---

## 📈 Benefits

- Reduces manual permission handling
- Improves security structure
- Scales easily for large applications
- Clean separation of roles and permissions

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch  
3. Commit changes  
4. Push branch  
5. Open Pull Request  

---

## 👨‍💻 Author

**Shehzad**

Full Stack Developer  
GitHub: https://github.com/shehzad-official

---

⭐ If you find this project useful, consider giving it a star.
