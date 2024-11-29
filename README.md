
# Notification Service

## Purpose
Sends notifications to users.

## Tech Stack
- Node.js
- RabbitMQ
- Firebase SDK

## Features
- Email notifications for shared files
- Push notifications for mobile devices

## Directory Structure
```plaintext
/src
  /workers          # Background workers for processing notifications
  /services         # Core business logic
  /adapters         # Interfaces for Firebase, email APIs, etc.
