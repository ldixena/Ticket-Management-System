# Ticket Management System

## Overview
The Ticket Management System is a web-based application developed using ASP.NET Core, C#, and SQL Server to manage customer issues, technical problems, and service requests efficiently. It provides a centralized platform for users and administrators to create, track, assign, and resolve support tickets.

## Features

### User Features
- User registration and secure login
- Create and submit support tickets
- Set ticket priority and category
- Track ticket status and progress
- View ticket details and conversation history
- Reply to support messages
- Upload attachments
- View personal ticket history

### Admin Features
- Admin dashboard with ticket statistics
- View and manage all tickets
- Assign tickets to support staff
- Update ticket status and priority
- Manage users and support requests
- Communicate with users through ticket replies
- Add internal notes
- Monitor ticket resolution and generate reports

## Ticket Status
- Open
- In Progress
- Pending
- Resolved
- Closed

## Technologies Used
- **Backend:** C#, ASP.NET Core
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Database:** Microsoft SQL Server
- **ORM:** Entity Framework Core
- **Authentication:** ASP.NET Core Identity / JWT Authentication
- **Tools:** Visual Studio 2022, SQL Server Management Studio, Git

## Project Structure

```text
TicketManagementSystem/
├── Controllers/
├── Models/
├── Views/
├── Data/
├── Services/
├── DTOs/
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
├── appsettings
