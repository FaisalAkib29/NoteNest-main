## NoteNest-main
NoteNest is a web-based personal cloud drive for managing notes and files. It allows users to upload, organize, share, and download files and folders securely. The application is built with PHP and MySQL, and features a modern, responsive interface.

## Features
- User registration and login
- Dashboard with quick access to personal, shared, favorite, and todo sections
- Upload, preview, download, rename, and delete files (any file type supported)
- Organize files in unlimited nested folders
- Share files and folders with other users (view-only)
- Manage shared access and revoke sharing
- Mark files and folders as favorites for quick access
- Todo list with reminders and notifications
- User profile management (name, phone, gender, photo, password)
- Notifications for sharing and todo reminders
- Security: user data isolation, input validation, password hashing, prepared statements


## Tech Stack

- PHP (8.x recommended)
- MySQL
- HTML
- Bootstrap 5
- Font Awesome

## Main Files & Structure

### Core Pages
- `dashboard.php` — Main user dashboard
- `my_note_nest.php` — Personal files and folder management
- `shared_note_nest.php` — Files and folders shared with the user
- `favorites.php` — Favorites management
- `todo.php` — To-do list and reminders
- `profile.php` — User profile management

### Authentication
- `register.php` — User registration
- `login.php` — User login
- `logout.php` — User logout

### File & Sharing Management
- `share.php` — Share files and folders
- `share_management.php` — Manage and revoke shared access
- `note_download.php` — Secure file download
- `note_preview.php` — File preview functionality

### Notifications & Background Tasks
- `notifications.php` — Notification system
- `cron/todo_reminder.php` — Automated to-do reminders

### Supporting Directories
- `includes/` — Authentication, database connection, common functions, navigation
- `uploads/notes/` — User uploaded files
- `img/user_photos/` — User profile photos


