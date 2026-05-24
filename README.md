# UniLost 🔍

A web platform that helps university students report and recover lost or found items on campus — reducing the chaos of lost belongings through a simple, centralized system.

## Motivation
Lost items on campus usually end up posted on random WhatsApp groups or physical bulletin boards with no follow-up. UniLost centralizes this process and gives items a proper lifecycle — from reported to resolved.

## Features
- Register / Login with session management
- Post lost or found items with descriptions
- Browse and search all active items
- View item details
- Manage your posts (delete / mark as resolved)

## Tech Stack
- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: PHP
- Database: MySQL

## Database Schema
- `users` — stores student accounts
- `items` — stores lost/found item listings with status tracking

## Installation
1. Clone the repo
2. Import `database.sql` into MySQL
3. Configure credentials in `db.php`
4. Run on localhost via XAMPP

## Status
V1 complete. Currently rebuilding with a modern stack (React + Node.js) 
with planned AI-powered item matching feature.

## Author
Med Yassine Ben Salem — [LinkedIn](https://www.linkedin.com/in/med-yassine-bensalem)
