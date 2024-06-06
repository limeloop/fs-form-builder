# Full Stack Form Builder

## Overview

This project is a Full Stack Form Builder application designed to create, manage, and publish forms using modern web technologies. It leverages React with TypeScript for the frontend, Dnd-Kit for drag-and-drop functionality, Vercel PostgreSQL with Prisma for the database, and Tailwind CSS for styling.

## Features

- **Responsive Design:** Fully responsive to ensure compatibility across various devices.
- **Drag and Drop Form Builder:** Create forms using an intuitive drag-and-drop interface.
- **Layout Fields:** Includes Title, SubTitle, Spacer, Separator, and Paragraph components.
- **Form Fields:** Supports Text, Number, Select, Date, Checkbox, and Textarea fields.
- **Customizable Fields:** Easily add and customize new fields.
- **Form Preview Dialog:** Preview forms before sharing or publishing.
- **Shareable Form URL:** Share forms via a unique URL.
- **Form Submission and Validation:** Handle form submissions and validations efficiently.
- **Form Stats:** Track form visits and submissions.

## Technologies Used

- **Frontend:** Next.js 13 (AppRouter), React, TypeScript, Dnd-Kit, Shadcn UI
- **Backend:** Node.js, Vercel PostgreSQL, Prisma
- **Styling:** Tailwind CSS
- **Utilities:** ESLint, Prettier, React Hook Form, Zod

## Getting Started

### Prerequisites

- Node.js (version 14.x or higher)
- PostgreSQL
- npm or yarn

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/maesterfox/fs-form-builder.git
   cd full-stack-form-builder
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Set up the database:**
   Ensure PostgreSQL is running and create a database. Update the Prisma configuration with your database credentials.

4. **Generate Prisma client:**
   ```sh
   npx prisma generate
   ```

5. **Run database migrations:**
   ```sh
   npx prisma migrate dev --name init
   ```

### Running the Application

1. **Development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```
   The application will be available at `http://localhost:3000`.

2. **Build for production:**
   ```sh
   npm run build
   # or
   yarn build
   ```

3. **Start the production server:**
   ```sh
   npm start
   # or
   yarn start
   ```

### Scripts

- `dev`: Starts the development server.
- `build`: Builds the application for production.
- `start`: Starts the production server.
- `lint`: Runs ESLint for code linting.
- `postinstall`: Generates the Prisma client.

## Project Structure

- **`/app`**: Next.js App Router structure
- **`/components`**: React components
- **`/styles`**: Tailwind CSS styles
- **`/prisma`**: Prisma schema and migration files
- **`/lib`**: Utility functions and configurations

## Key Files

- **`package.json`**: Project dependencies and scripts
- **`tsconfig.json`**: TypeScript configuration
- **`tailwind.config.js`**: Tailwind CSS configuration
- **`prisma/schema.prisma`**: Prisma schema definition
- **`next.config.js`**: Next.js configuration

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please reach out to [david.fox@davidfoxdev.co.uk].

---

This README provides a comprehensive guide to set up, run, and contribute to the Full Stack Form Builder project. It covers the essential aspects needed to understand and work with the project effectively.