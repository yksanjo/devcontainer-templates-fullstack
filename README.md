# Dev Container Template - Full-Stack (Node.js + React)

Pre-configured containerized development environment for full-stack web applications with Node.js backend and React/Vue frontend.

## Features

- **Node.js 20** with npm
- **TypeScript** support
- **React** + **Vue** support
- **Tailwind CSS** support
- **ESLint** + **Prettier** for code quality
- **Nodemon** for auto-restart during development
- **PM2** for production process management
- **Concurrently** for running multiple scripts
- **SQLTools** for database management
- Markdown linting
- Auto Rename Tag
- Emmet support

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - React development server
- `3001` - Alternative development port
- `5000` - Backend API server
- `5173` - Vite/Vue development server
- `8080` - General HTTP server
- `9229` - Node.js debugger

### Extensions Included
- ESLint
- Prettier
- PowerShell
- Docker
- TypeScript
- Azure Repos
- SQLTools
- Path IntelliSense
- IntelliCode
- Tailwind CSS
- React/ES7+ snippets
- Auto Rename Tag
- HTML/CSS Sort
- Markdownlint

### Post-Create Commands
- Installs TypeScript, Nodemon, PM2, Concurrently globally
- Installs create-react-app and vue-cli
- Runs `npm install` in your project

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
