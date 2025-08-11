# Getting Started with Remix

This guide will walk you through the process of creating a new Remix application.

## Prerequisites

Before you begin, make sure you have the following installed on your system:

- Node.js (v14 or later)
- npm, yarn, pnpm, or bun

## Creating a New Remix App

The easiest way to start a new Remix project is by using the `create-remix` command-line interface (CLI).

You can run the following command in your terminal:

```bash
npx create-remix@latest
```

This command will prompt you with a few questions to configure your new project, such as the project name and which template to use.

### Using a Specific Template

If you want to use a specific template, you can use the `--template` flag. For example, to create a new project using the official "indie-stack" template, you would run:

```bash
npx create-remix@latest --template remix-run/indie-stack
```

### Specifying a Project Directory

You can also specify the directory where you want to create the project:

```bash
npx create-remix@latest ./my-remix-app
```

## Available Package Managers

You can use your preferred package manager to create a new Remix app:

- **npm:** `npm create remix@latest`
- **Yarn:** `yarn create remix@latest`
- **pnpm:** `pnpm create remix@latest`
- **Bun:** `bunx create-remix@latest`

## Running the Development Server

Once your project is created, navigate to the project directory:

```bash
cd my-remix-app
```

Then, you can start the development server:

```bash
npm run dev
```

This will start the development server, and you can view your new Remix app by opening your browser to `http://localhost:3000`.

## Additional Resources

- [Remix Quick Start Guide](https://remix.run/docs/en/main/start/quickstart)
- [create-remix CLI Documentation](https://remix.run/docs/en/main/other-api/create-remix)
- [Remix Templates](https://remix.run/docs/en/main/guides/templates)