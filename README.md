# 📋 ABITUR (WPF + PostgreSQL)

> Десктопное WPF-приложение на C# для управления базой данных абитуриентов учебного заведения с разграничением прав доступа и шифрованием данных.
>
> A C# WPF desktop application for managing a college's applicant database with role-based access control and data encryption.

---

## 🇷🇺 Русский

### ✨ Возможности

- 🔐 **Авторизация** с разграничением прав (администратор / пользователь)
- 👥 **Просмотр абитуриентов** — полный доступ для админа, ограниченный для пользователя
- ✏️ **CRUD-операции** над абитуриентами, пользователями и группами
- 🔒 **Шифрование данных** (логины, пароли, ФИО, телефоны) собственным симметричным шифром
- 📝 **Логирование** всех действий пользователей
- 🗄️ **PostgreSQL** через Npgsql с автоинициализацией таблиц
- 🎨 **Динамический интерфейс** — формы меняются в зависимости от операции

### 🛠️ Стек технологий

| Технология | Назначение |
|-----------|-----------|
| **C# / .NET** | Язык и платформа |
| **WPF** | Графический интерфейс |
| **PostgreSQL** | База данных |
| **Npgsql** | Драйвер подключения к БД |

### 🚀 Запуск

1. Установите **PostgreSQL** и создайте БД
2. Настройте строку подключения в классе `DataBase`:
   ```csharp
   "Host=...t; Port=5432; Database=...; Username=...; Password=...;"
   ```
3. Откройте проект в **Visual Studio** и запустите

#### 🔑 Учётные записи по умолчанию

| Логин | Пароль | Роль |
|-------|--------|------|
| `admin` | `admin123` | Администратор |
| `user` | `user123` | Пользователь |

---

## 🇬🇧 English

### ✨ Features

- 🔐 **Authentication** with role-based access (admin / user)
- 👥 **Applicant viewer** — full access for admins, limited for users
- ✏️ **CRUD operations** on applicants, users, and groups
- 🔒 **Data encryption** (logins, passwords, names, phones) via custom symmetric cipher
- 📝 **Action logging** for all user operations
- 🗄️ **PostgreSQL** via Npgsql with automatic table initialization
- 🎨 **Dynamic UI** — forms change based on the selected operation

### 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **C# / .NET** | Language & platform |
| **WPF** | GUI framework |
| **PostgreSQL** | Database |
| **Npgsql** | PostgreSQL driver |

### 🚀 Getting Started

1. Install **PostgreSQL** and create the database
2. Configure the connection string in the `DataBase` class:
   ```csharp
   "Host=...t; Port=5432; Database=...; Username=...; Password=...;"
   ```
3. Open the project in **Visual Studio** and run it

#### 🔑 Default Accounts

| Login | Password | Role |
|-------|----------|------|
| `admin` | `admin123` | Administrator |
| `user` | `user123` | User |

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0**.
