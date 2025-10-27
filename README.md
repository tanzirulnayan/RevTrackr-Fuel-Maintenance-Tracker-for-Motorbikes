# 🏍️ RevTrackr - Fuel Maintenance Tracker for Motorbikes

> **A modern platform for riders to record refuels, rides, and maintenance — and analyze fuel efficiency.**  
> Built with **.NET 8**, **Clean Architecture**, **CQRS + MediatR**, **EF Core**, and an **event-driven backend** powered by **RabbitMQ**, **MassTransit**, and **Saga workflows**.

---

## 🚀 Overview

**MotoMaintainer** is a scalable, event-driven web platform for managing every aspect of your motorcycle’s performance and upkeep.  
Riders can log **refuels, rides, and maintenance activities**, track **fuel efficiency**, and gain insights through **ETL-powered analytics**.

This project demonstrates advanced architectural and design concepts in a real-world **.NET 8 Web API** application.

---

## 🧱 Core Architecture & Design

| Layer | Description |
|-------|--------------|
| **Domain** | Core business logic, entities, value objects, and domain events. |
| **Application** | CQRS + MediatR commands, queries, handlers, and interfaces. |
| **Infrastructure** | EF Core (Repository + UnitOfWork), MassTransit, RabbitMQ, ADF integration. |
| **API** | REST, GraphQL, and gRPC endpoints with JWT authentication and middleware. |

---

## 🧩 Key Features

✅ **Clean Architecture** — strict separation of concerns and testable design.  
✅ **CQRS + MediatR** — vertical slicing for commands and queries.  
✅ **Repository + Unit of Work** — consistent data access with EF Core 8.  
✅ **JWT Authentication** — secure endpoints with role-based authorization.  
✅ **Multi-API Access** — REST for apps, GraphQL for analytics, gRPC for devices.  
✅ **Event-Driven Backend** — RabbitMQ + MassTransit + Saga orchestration.  
✅ **ADF ETL Pipelines** — push aggregated metrics to a data warehouse.  
✅ **API Versioning, Middleware, and Logging** — extensible and production-ready.  

---

## 🏗️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Framework** | .NET 8 Web API, C# 12 |
| **Architecture** | Clean Architecture, CQRS, SOLID |
| **Database** | MSSQL, EF Core 8, Repository & UoW |
| **Messaging** | RabbitMQ, MassTransit, Saga Pattern |
| **Auth** | JWT Bearer, ASP.NET Core Identity |
| **API Layers** | REST, GraphQL (HotChocolate), gRPC |
| **ETL & Analytics** | Azure Data Factory (ADF), Synapse / PowerBI |
| **Testing** | xUnit, Moq, EF Core InMemory / SQLite |
| **DevOps** | Docker, GitHub Actions CI/CD |
| **Logging & Monitoring** | Serilog, OpenTelemetry (optional) |
