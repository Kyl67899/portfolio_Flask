<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="portfolio_Flask.png" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>

# PORTFOLIO_FLASK

<em>Showcase Your Skills, Inspire Your Audience Effortlessly</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/Kyl67899/portfolio_Flask?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/Kyl67899/portfolio_Flask?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/Kyl67899/portfolio_Flask?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Flask-000000.svg?style=flat&logo=Flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00.svg?style=flat&logo=SQLAlchemy&logoColor=white" alt="SQLAlchemy">
<img src="https://img.shields.io/badge/.ENV-ECD53F.svg?style=flat&logo=dotenv&logoColor=black" alt=".ENV">
<img src="https://img.shields.io/badge/Gunicorn-499848.svg?style=flat&logo=Gunicorn&logoColor=white" alt="Gunicorn">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">

</div>
<br>

---

## Table of Contents

- [PORTFOLIO\_FLASK](#portfolio_flask)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Project Structure](#project-structure)
    - [Project Index](#project-index)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)

---

## Overview

portfolio_Flask is a Flask-based web application designed to serve as a personal portfolio platform, enabling developers to showcase projects, manage contacts, and administer content seamlessly. It integrates deployment configurations, core application logic, and dependency management into a cohesive system.

**Why portfolio_Flask?**

This project simplifies building and deploying a dynamic portfolio website. The core features include:

- 🛠️ **Deployment Orchestration:** Uses render.yaml to streamline hosting and environment setup.
- 🌐 **Dynamic Content Rendering:** Built with Flask to serve interactive project and contact pages.
- 🔐 **User Authentication & Admin:** Facilitates secure management of content and contacts.
- 📦 **Environment Consistency:** Managed dependencies via requirements.txt for reliable setups.
- 📊 **Full-stack Functionality:** Integrates project management, contact handling, and admin controls.

---

## Features

|      | Component            | Details                                                                                     |
| :--- | :------------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**     | <ul><li>Flask-based MVC pattern</li><li>Separation of concerns with blueprints</li><li>Uses SQLAlchemy ORM</li></ul> |
| 🔩 | **Code Quality**     | <ul><li>PEP8 compliant</li><li>Consistent naming conventions</li><li>Uses type hints (via `typing_extensions`)</li></ul> |
| 📄 | **Documentation**    | <ul><li>Basic README with project overview</li><li>Uses docstrings for functions/classes</li><li>Configuration via `render.yaml` and `.env` files</li></ul> |
| 🔌 | **Integrations**     | <ul><li>Flask extensions: `Flask-Bcrypt`, `Flask-Migrate`, `Flask-Admin`, `Flask-SQLAlchemy`</li><li>Database migrations with Alembic</li><li>Environment variables with `python-dotenv`</li></ul> |
| 🧩 | **Modularity**       | <ul><li>Blueprints for modular routes</li><li>Separate models, forms, and views</li><li>Configurable via environment variables</li></ul> |
| 🧪 | **Testing**          | <ul><li>Not explicitly detailed; likely minimal or manual testing</li><li>Dependencies suggest potential for unit tests with `pytest` (not confirmed)</li></ul> |
| ⚡️  | **Performance**      | <ul><li>Uses `gunicorn` for WSGI server</li><li>Optimized database interactions with SQLAlchemy</li></ul> |
| 🛡️ | **Security**         | <ul><li>Password hashing with `Flask-Bcrypt`</li><li>Secure session management via `itsdangerous`</li><li>Environment variables for sensitive info</li></ul> |
| 📦 | **Dependencies**     | <ul><li>Core: `Flask`, `SQLAlchemy`, `Jinja2`, `Werkzeug`</li><li>Security: `bcrypt`, `Flask-Bcrypt`</li><li>Migration: `Flask-Migrate`, `alembic`</li><li>Form handling: `WTForms`</li><li>Others: `dotenv`, `pytz`, `MarkupSafe`, `packaging`</li></ul> |

---

## Project Structure

```sh
└── portfolio_Flask/
    ├── README.md
    ├── app.py
    ├── render.yaml
    └── requirements.txt
```

---

### Project Index

<details open>
	<summary><b><code>PORTFOLIO_FLASK/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/Kyl67899/portfolio_Flask/blob/master/render.yaml'>render.yaml</a></b></td>
					<td style='padding: 8px;'>- Defines the deployment configuration for a web service named portfolio_flask, specifying environment setup, build, and start commands<br>- It orchestrates the deployment process within the overall architecture, ensuring the Flask application is correctly installed and launched in a Python environment, thereby enabling seamless hosting and accessibility of the portfolio website.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/Kyl67899/portfolio_Flask/blob/master/app.py'>app.py</a></b></td>
					<td style='padding: 8px;'>- Provides the core web application logic for a portfolio platform built with Flask, integrating project management, contact handling, and admin functionalities<br>- Facilitates dynamic content rendering, user authentication, and database interactions with PostgreSQL, enabling efficient management and display of projects, contact messages, and administrative controls within a cohesive architecture.
					<strong>Need to create a database and add the string connection to the .env file. DO NOT EXPOSE YOUR API KEY</strong></td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/Kyl67899/portfolio_Flask/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the portfolio Flask application, outlining its role within the project architecture<br>- It highlights how the application serves as the core interface for showcasing personal projects and skills, facilitating user interaction and presenting dynamic content<br>- This README contextualizes the project’s purpose within the broader system, guiding users and contributors on its functionality and scope.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/Kyl67899/portfolio_Flask/blob/master/requirements.txt'>requirements.txt</a></b></td>
					<td style='padding: 8px;'>- Defines project dependencies essential for building and running a Flask-based web application with database migration, user authentication, and administrative interfaces<br>- Ensures consistent environment setup, facilitating smooth development, deployment, and maintenance within the overall architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python
- **Package Manager:** Pip

### Installation

Build portfolio_Flask from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/Kyl67899/portfolio_Flask
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd portfolio_Flask
    ```

3. **Install the dependencies:**

**Using [pip](https://pypi.org/project/pip/):**

```sh
❯ pip install -r requirements.txt
```

### Usage

Run the project with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
python {entrypoint}
```

### Testing

Portfolio_flask uses the {__test_framework__} test framework. Run the test suite with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
pytest
```

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
