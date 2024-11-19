# Limeloop Form Builder

## Overview

Package to create forms by drag and dropping elements. Started from [this project](https://github.com/maesterfox/fs-form-builder).

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
- yarn

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/maesterfox/fs-form-builder.git
   ```

2. **Install dependencies:**
   ```sh
   yarn install
   ```

### Development

1. **Link a development package from root:**
   ```sh
   yarn link
   ```

2. **Go to the consuming app where you will use the package and link the package there with:**
   ```sh
   yarn link limeloop-react-form
   ```

3. **Start server of the consuming app:**
   ```sh
   yarn start
   ```
4. **Every time you make changes you will see them on the consuming app.**

### Scripts

- `build`: Builds the application for production.

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