# 10x-cards

## Table of Contents

- [Project Description](#project-description)
- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Project Description

10x-cards is a user-friendly flashcards application that enables users to quickly create, manage, and study flashcards. Leveraging AI-powered suggestions via an LLM API, it reduces the time and effort required to create effective flashcards for spaced repetition learning. The app supports both automatic flashcard generation and manual flashcard management (creation, editing, and deletion), complete with user authentication and account management.

## Tech Stack

- **Frontend:** Astro 5, React 19, TypeScript 5, Tailwind 4, Shadcn/ui
- **Backend:** Supabase for database management and user authentication
- **AI Integration:** Openrouter.ai for accessing various LLM models to generate flashcard suggestions
- **CI/CD & Hosting:** GitHub Actions and DigitalOcean (using Docker)

## Getting Started Locally

1. **Prerequisites:**

   - [Node.js](https://nodejs.org/) (version specified in the `.nvmrc` file: 22.14.0)

2. **Clone the repository:**

   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

3. **Install dependencies:**

   ```sh
   npm install
   ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

## Available Scripts

- `npm run dev` - Runs the development server.
- `npm run build` - Builds the project for production.
- `npm run preview` - Serves the production build locally.
- `npm run astro` - Executes Astro CLI commands.
- `npm run lint` - Runs ESLint to analyze code quality.
- `npm run lint:fix` - Automatically fixes linting errors.
- `npm run format` - Formats code using Prettier.

## Project Scope

- **Automatic Flashcard Generation:** Use AI to generate flashcards from user-provided text.
- **Manual Flashcard Management:** Create, edit, and delete flashcards manually.
- **User Authentication:** Secure registration and login functionality.
- **Spaced Repetition Integration:** Incorporates algorithms to optimize learning sessions.
- **Data Tracking & Privacy:** Tracks flashcard generation metrics while ensuring GDPR-compliant data handling.

## Project Status

- **Version:** 0.0.1 (MVP)
- Currently in early development with ongoing enhancements and optimizations planned.

## License

MIT License
