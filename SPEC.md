# AI Agent Rental Platform

## Project Overview
AgentHub is building a SaaS platform where companies can rent AI agents — pre-configured intelligent assistants that can be equipped with different skills (capabilities such as browsing the web, reading documents, or managing calendars) and deployed for specific business tasks.

## Features
- Sidebar navigation to the following sections:
    - Dashboard
    - User Management
    - Agent Management
    - Skills
    - Agent Contracts
    - Error Log
- Dark mode toggle button in the navbar
    - Utilizing TailwindCSS's `dark:` utility

## Data Models
```ts
interface User {
    name: string;
    email: string;
    plan: "Basic" | "Pro" | "Unlimited";
    status: "active" | "inactive";
}
```

## Goals
- A responsive layout using TailwindCSS delivered via a CDN

## Anti-Goals
- Things that you want to avoid to make sure your project is successful
