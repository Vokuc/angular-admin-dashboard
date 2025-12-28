# Angular Admin Dashboard

A real-world Angular admin dashboard demonstrating authentication, protected routes, API integration, forms, modals, and clean project architecture.

## Features
- JWT-based authentication
- Protected routes using route guards
- HTTP interceptors for auth headers
- CRUD operations with a mock API
- Reactive forms with validation
- Modal-driven UI flows
- Role-based UI permissions
- Environment-based configuration

## Tech Stack
- Angular
- TypeScript
- RxJS
- Bootstrap / Tailwind (pick one)
- JSON Server (mock backend)

## Project Structure
src/app/
- core/        # auth, guards, interceptors
- shared/      # reusable components & services
- features/    # feature-based modules

## Setup
1. Clone the repo
2. npm install
3. npm run start
4. npm run api

## Why This Project Exists
This project mirrors how Angular is used in real production environments, focusing on maintainable structure, clean data flow, and practical feature implementation rather than toy examples.
