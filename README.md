# Laravel 11 Task Management API

REST API for managing tasks with CRUD operations. Built for TCS interview prep.

## Features
- **CRUD**: Create, Read, Update, Delete tasks
- **Validation**: Title required, status must be `pending`, `in-progress`, or `completed`
- **Filtering**: `GET /api/tasks?status=pending`
- **Database**: MySQL with Eloquent ORM and migrations
- **Tested**: All endpoints verified with Postman

## Tech Stack
| Backend | Database | Tools |
| --- | --- | --- |
| PHP 8.2, Laravel 11 | MySQL 8.0 | Composer, Git, Postman |

## Setup Instructions
```bash
git clone https://github.com/kajishivleela-rgb/laravel-task-api.git
cd laravel-task-api
composer install
cp .env.example .env
