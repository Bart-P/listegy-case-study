# Listegy Case Study

Listegy is an AI-assisted e-commerce listing workflow tool built with Laravel, Vue and PostgreSQL.

The project helps structure the process of creating and optimizing product content for e-commerce listings. It focuses on product data, personas, keywords, reusable workflows and AI-assisted generation steps with manual control.

## Status

Active development.  
The core application structure, data models and workflow screens are in place. The AI integration is currently being implemented as part of the MVP.

The source code is private because the project contains product-specific logic, internal workflow concepts and potential commercial use.

## Tech Stack

- Laravel
- Vue.js
- PostgreSQL
- Tailwind CSS
- shadcn-vue
- API integrations
- AI-assisted workflows

## Problem

E-commerce teams often create product texts, personas, keywords and listing content across scattered documents, prompts and spreadsheets.

This leads to:

- inconsistent workflows
- lost context
- repeated manual work
- hard-to-reuse prompts
- no structured history of decisions and generated outputs

Listegy is designed to turn that process into a structured application with saved data, reusable workflows and manual review steps.

## Core Features

- product and company data management
- structured workflow for product content creation
- persona and keyword handling
- reusable prompt and workflow structures
- AI-assisted generation steps
- manual review and editing before final output
- PostgreSQL-backed data storage

## Screenshots

### Listing text workflow

![Listing text workflow](screenshots/01-text-generation.png)

### Product image selection

![Product image selection](screenshots/02-image-selection.png)

### Lifestyle image generation workflow

![Lifestyle image generation workflow](screenshots/03-image-generation.png)

## Architecture Overview

The application uses Laravel as the backend and Vue as the frontend.

Laravel handles routing, validation, persistence, business logic and API boundaries. Vue is used for the interactive application interface, forms, workflow screens and editing flows.

The AI integration is designed as a controlled workflow step rather than full automation. The goal is to assist the user while keeping review, editing and decision-making inside the application.

## My Role

I designed and developed the application as a solo project.

My work includes:

- application structure and data modelling
- Laravel backend implementation
- Vue frontend implementation
- workflow design
- UI implementation with Tailwind CSS and shadcn-vue
- planning of AI-assisted generation steps
- PostgreSQL setup and application persistence

## What This Project Shows

- building internal tools with Laravel and Vue
- translating e-commerce processes into software workflows
- working with relational data models
- structuring AI-assisted processes in a controlled application
- building practical software for real operational use cases

## Notes

This repository is a public case study only.  
The production source code remains private.
