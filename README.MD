# Firebase OAuth Authentication and Authorization API

This repository contains a generic Authentication and Authorization API built using Firebase OAuth. The API provides endpoints for user authentication via OAuth providers (like Google, Facebook, etc.) and handles user authorization with role-based access control.

## Features

- **OAuth Authentication**: Secure user authentication using Firebase OAuth.
- **Role-Based Authorization**: Assign roles to users and manage permissions to control access to different API endpoints.
- **Token Management**: Handle and verify JWT tokens to secure API endpoints.
- **Scalable**: Easy to extend with additional OAuth providers or custom roles.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:

- [Node.js](https://nodejs.org/en/download/) installed
- Firebase project setup with OAuth providers enabled
- Firebase Admin SDK service account key

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/asad-ishtiaque/backend-oauth.git
   cd backend-oauth
