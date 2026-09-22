# Mr Vitamins E-Commerce

A full-stack e-commerce web application for Mr Vitamins, built to provide customers with a simple way to browse vitamin and supplement products, manage their basket, and place orders online.

This project is being developed as a full-stack software engineering project using React, FastAPI, and PostgreSQL.

## Tech Stack

### Frontend
- React
- JavaScript

### Backend
- FastAPI
- Python

### Database
- PostgreSQL

## Planned Features

- Browse vitamin and supplement products
- View individual product information
- Search and filter products
- Shopping basket
- Customer checkout
- Customer accounts
- Order history
- Stock management
- Admin dashboard
- Product management
- Secure authentication

## Architecture

```mermaid
flowchart LR
    A[React Frontend] -->|REST API| B[FastAPI Backend]
    B -->|SQL| C[(PostgreSQL Database)]