# 🎧 Calico — Full‑Stack LoFi Music & Productivity Platform

![Frontend](https://img.shields.io/badge/Frontend-Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![Backend](https://img.shields.io/badge/Backend-.NET_8_API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Auth](https://img.shields.io/badge/Auth-Supabase_JWT-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Database](https://img.shields.io/badge/Database-SQLite_/_SQL_Server-336791?style=for-the-badge&logo=sqlite&logoColor=white)
![Design](https://img.shields.io/badge/Design-UML_/_Figma-000000?style=for-the-badge&logo=figma&logoColor=white)


Calico is a full‑stack LoFi music and productivity platform built as part of a collaborative group project.
It combines a Blazor frontend with a .NET 8 Web API backend, delivering music discovery, playlist management, productivity tools, and secure authentication through a clean, scalable architecture.

# 🚀 Overview

Calico is designed as a real‑world, production‑style application featuring:

* Component‑driven Blazor UI

* Secure Supabase JWT authentication

* REST API backend with layered architecture

* SQLite (dev) + SQL Server (prod)

* Music, playlists, projects, and task‑timer features

* Automated testing across frontend and backend

* UML, Figma, and Canva‑based design planning

# 🧰 Full‑Stack Tech Summary

| Layer | Technologies |
| --- | --- |
| **Frontend** | Blazor, C#, Razor Components, HttpClient |
| **Backend** | ASP.NET Core Web API (.NET 8) |
| **Auth** | Supabase JWT (cookie‑based) |
| **Database** | SQLite (Dev), SQL Server (Prod) |
| **ORM** | Entity Framework Core |
| **Media Integration** | YouTube API |
| **Testing** | NUnit, Moq, Shouldly |
| **Design Tools** | Figma, Canva, Diagrams.net |

# 🎵 Core Features (Full‑Stack)
## Music & Media
* LoFi music discovery

* Featured recommendations

* Embedded YouTube playback

* Playlist creation & management

## Productivity Tools
* Task timer

* Project tracking

* Dashboard summaries

## User Management
* Registration & login

* JWT authentication (Supabase)

* Profile updates

## System Features
* Health checks (/health)

* Swagger API documentation

* Automatic DB creation/migration

# 🏗️ Architecture (High‑Level)

Frontend (Blazor)
    ↓
HttpClient REST Calls
    ↓
Backend API (.NET 8)
    ↓
Services (Business Logic)
    ↓
Repositories (Data Access)
    ↓
Entity Framework Core
    ↓
SQLite / SQL Server

# 🧪 Testing
## Frontend
* Component logic

* HttpClient behaviour

## Backend
* Repository tests

* Service tests

* Controller tests

* Tools: NUnit, Moq, Shouldly

# 🎨 Design & Planning
* UML / System Diagram

* Figma Ideation Board

* Canva UI Design

(Links included in the individual frontend/backend READMEs.)

# 📁 Project Structure (Full‑Stack)

calico/
├── frontend/
│   ├── Components/
│   ├── Pages/
│   ├── Models/
│   └── wwwroot/
│
├── backend/
│   ├── Controllers/
│   ├── Service/
│   ├── Repository/
│   ├── Database/
│   ├── HealthChecks/
│   └── Data Models/
│
└── tests/
    ├── frontend-tests/
    └── backend-tests/

