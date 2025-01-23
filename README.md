# Fullstack Inventory Management Dashboard

## Introduction

This is a Fullstack Inventory Management Dashboard designed to streamline inventory tracking and management. It features a modern and responsive UI, robust backend, and seamless cloud integration.

---

## Tech Stack

- **Frontend**:

  - Next.js
  - Tailwind CSS
  - Redux Toolkit
  - Redux Toolkit Query
  - Material UI Data Grid

- **Backend**:

  - Node.js
  - Prisma

- **Cloud Services**:

  - AWS EC2
  - AWS RDS
  - AWS API Gateway
  - AWS Amplify
  - AWS S3

---

## Features

- **Inventory Dashboard**: Manage products, categories, and stock levels.
- **Data Grid**: Interactive table using Material UI Data Grid.
- **Authentication**: Secure user login and role-based access control.
- **Cloud Integration**: AWS services for hosting, API management, and storage.
- **Database Management**: Leverages Prisma ORM and AWS RDS for efficient data handling.

---

## How to Set Up

### Prerequisites

1. Install Node.js and npm.
2. Install the AWS CLI and configure it with your credentials.
3. Set up a PostgreSQL instance on AWS RDS.

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/Prashantdhaka23/inventory-management.git
   cd inventory-management
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure Prisma:

   - Update the `prisma/schema.prisma` file with your database connection string.

4. Apply database migrations:

   ```bash
   npx prisma migrate dev
   ```

5. Seed the database:

   ```bash
   npx prisma db seed
   ```

6. Start the development server:

   ```bash
   npm run dev
   ```

7. Deploy to AWS using your preferred deployment strategy.

---

## Project Structure

- **Frontend**: Located in the `pages` and `components` directories.
- **Backend**: API routes and Prisma configuration in the `api` directory.
- **Cloud Configuration**: AWS scripts and setup instructions.

---

## Additional Resources

1. **Data Model Diagram**

   - Diagram showcasing relationships between entities.

2. **Prisma Schema File**

   - Includes the database schema for seamless migrations.

3. **AWS Commands**

   - List of useful AWS CLI commands for deployment and configuration.

---

## Contribution

This is a personal project, but feel free to share suggestions or report issues to improve the application.

---

## License

This project is licensed under the MIT License.

