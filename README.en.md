<div align="center">

# Construction Project CRM

### An operational workspace for construction project management

A full-stack CRM bringing projects, work stages, materials, expenses, documents, team management, and analytics into one workspace.

[![Русский](https://img.shields.io/badge/Русский-EDECE9?style=for-the-badge&logoColor=31302E)](./README.md)
[![English](https://img.shields.io/badge/English-0075DE?style=for-the-badge)](./README.en.md)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Go](https://img.shields.io/badge/Go-20232A?style=flat-square&logo=go&logoColor=00ADD8)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-20232A?style=flat-square&logo=postgresql&logoColor=7DA9D8)
![Vite](https://img.shields.io/badge/Vite-20232A?style=flat-square&logo=vite&logoColor=FFC85A)
![Full Stack](https://img.shields.io/badge/Full--stack-case_study-31302E?style=flat-square)
![Source](https://img.shields.io/badge/source-private-615D59?style=flat-square&logo=github)

</div>

![Construction CRM projects screen](assets/projects.jpg)

> [!NOTE]
> This is a public visual case study. All names, users, phone numbers, amounts, and dates shown in the screenshots are fictional. The repository contains no product source code, API endpoints, infrastructure configuration, or production data.

## Product overview

The CRM supports a construction company's daily operations from project registration to completion. Teams use one interface to track stages and deadlines, structure work, record expenses and materials, store documents, and manage employee access.

| Area | Implemented workflows |
| :-- | :-- |
| **Projects** | Creation, search, sorting, statuses, budgets, and deadlines |
| **Work breakdown** | Sections, subsections, participants, and permissions |
| **Expenses** | Manual entry, import, photos, and change history |
| **Materials** | Shared catalog, measurement units, and material sets |
| **Documents** | File uploads and type-based grouping |
| **Team** | Registration, moderation, roles, and blocking |
| **Analytics** | Summary metrics, status distribution, and monthly dynamics |

## My role

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Frontend</h3>
      <p>Migrated business workflows from React Native to React and built responsive layouts, role-aware navigation, forms, filters, states, and themes.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Backend</h3>
      <p>Built REST API functionality with Go and Gin, JWT authentication, role-based access, PostgreSQL integration, file handling, audit history, and imports.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Integration</h3>
      <p>Aligned API contracts, handled failure states, prepared production web builds, and integrated static asset delivery.</p>
    </td>
  </tr>
</table>

### Frontend

- migrated essential workflows from the mobile application to the web;
- developed project, analytics, materials, users, mail, and profile screens;
- implemented role-aware navigation and protected product areas;
- added search, filters, sorting, file uploads, and action confirmations;
- designed loading, error, empty, and validation states;
- unified reusable components, responsive layouts, and light and dark themes.

### Backend

- developed REST API functionality with Go and Gin;
- implemented JWT authentication, token refresh, and logout flows;
- supported role-based authorization for multiple employee categories;
- worked on projects, sections, subsections, participants, and access control;
- implemented materials, sets, expenses, photos, and file workflows;
- added action history, spreadsheet imports, and document processing;
- worked with PostgreSQL, migrations, and relational entities.

## Product interface

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Projects</strong><br><br>
      <img src="assets/projects.jpg" alt="Construction projects list" />
    </td>
    <td width="50%" valign="top">
      <strong>Analytics</strong><br><br>
      <img src="assets/analytics.jpg" alt="Construction projects analytics" />
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <strong>Materials and sets</strong><br><br>
      <img src="assets/materials.jpg" alt="Construction materials catalog" />
    </td>
  </tr>
</table>

## Architecture

![Full-stack CRM architecture](assets/architecture.png)

| Layer | Technologies and responsibilities |
| :-- | :-- |
| **Web** | React, React Router, Zustand, Motion, Vite |
| **API** | Go, Gin, JWT, role-based authorization |
| **Data** | PostgreSQL, pgx, SQL migrations |
| **Documents** | Excelize, PDF processing, file uploads |
| **Delivery** | Docker, production web build, static asset serving |

---

<div align="center">

**A visual case study of completed full-stack work. The product source code is intentionally kept private.**

[Русская версия](./README.md) · [Back to top](#construction-project-crm)

</div>
