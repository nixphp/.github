<p align="center">
  <img src="https://nixphp.github.io/docs/assets/nixphp-logo-small-square.png" alt="NixPHP Logo" width="160">
</p>

<p align="center">
  <strong>Minimal. Extendable. Just what you need.</strong><br>
  A lightweight PHP microframework designed to stay out of your way.<br>
  <em>As simple as possible, as flexible as necessary.</em>
</p>

<p align="center">
  <a href="https://github.com/nixphp/framework"><img alt="Framework" src="https://img.shields.io/badge/Core_Framework-nixphp%2Fframework-blue?style=flat-square"></a>
  <a href="https://nixphp.github.io/docs"><img alt="Docs" src="https://img.shields.io/badge/Docs-View_on_GitHub_Pages-brightgreen?style=flat-square"></a>
</p>

<div align="center" style="text-align: center;">

<!-- ![Commits](https://img.shields.io/github/commit-activity/m/nixphp/framework) -->
<!-- ![Last Commit](https://img.shields.io/github/last-commit/nixphp/framework) -->

<!-- ![Open Issues](https://img.shields.io/github/issues/nixphp/framework) -->
<!-- ![Open Pull Requests](https://img.shields.io/github/issues-pr/nixphp/framework) -->

</div>

---

## 🔧 What is NixPHP?

**NixPHP** is a microframework for developers who want **full control** over their stack.  
With only the essentials included, and everything else available via plugins.

It comes with:

- PSR-based architecture (PSR-3, PSR-4, PSR-7, PSR-11, PSR-18)
- Minimalist routing and dispatching
- Plugin system for optional components (views, forms, sessions, DB, etc.)
- Native PHP approach, no complex abstraction layers

📦 *Use what you need. Leave out what you don’t.*

---

## 🧩 Official Plugins

| Plugin                                                  | Description                            |
|---------------------------------------------------------|----------------------------------------|
| [`nixphp/view`](https://github.com/nixphp/view)         | Native PHP templating with layout blocks |
| [`nixphp/form`](https://github.com/nixphp/form)         | CSRF protection + form input memory    |
| [`nixphp/session`](https://github.com/nixphp/session)   | Session and flash message support      |
| [`nixphp/database`](https://github.com/nixphp/database) | PDO database connection helper         |
| [`nixphp/orm`](https://github.com/nixphp/orm)           | PDO object mapping for entities        |
| [`nixphp/i18n`](https://github.com/nixphp/i18n)         | Internationalization for your project  |
| [`nixphp/cli`](https://github.com/nixphp/cli)           | CLI applications and helpers           |
 | [`nixphp/mail`](https://github.com/nixphp/mail)         | Send emails with attachments           |
 | [`nixphp/client`](https://github.com/nixphp/client)     | Make simple HTTP requests              |
 | [`nixphp/queue`](https://github.com/nixphp/queue) | Queueing system for asynchronous tasks |
| ...more coming soon...                                  | Auth, etc.                     |

---

## 📚 Documentation

📘 Read the full docs at **[nixphp.github.io/docs](https://nixphp.github.io/docs)**

---

## 🚀 Get started

```bash
composer create-project nixphp/app my-app
