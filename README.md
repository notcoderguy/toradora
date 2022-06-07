# ToraDora

![ToraDora Logo](public/ToraDora-logo.svg "ToraDora Logo")

ToraDora is a ToDo webapp which helps to keep track of the work which enables you to schedule your tasks and projects with to do lists and a calendar.

## Roadmap

- [ ] Light/dark mode toggle
- [ ] Custom To-do Lists
- [ ] Drag and Drop
- [ ] Multi-language
- [ ] Sub-tasks
- [ ] Markdown Support
- [ ] Customizable user interface
- [ ] Boards
- [ ] Task Priorities
- [ ] Task Colors
- [ ] Task Time
- [ ] Repeating Event
- [ ] Notifications and reminders
- [ ] Privacy
- [ ] Standalone Portable Application

## Installation

- Clone the repository.
- Install Composer packages & NPM modules.

```powershell
composer update
npm i
```

- Create .env file for the application.

### Windows

```powershell
copy .env.example .env
```

### Linux

```bash
cp .env.example .env
```

- Generate Secret Key for the application.

```powershell
php artisan key:generate
```
