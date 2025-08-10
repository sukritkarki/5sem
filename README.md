# Stand with Nepal - Citizen Voice Platform

A modern citizen engagement platform built with React, TypeScript, and Tailwind CSS that enables citizens to report local issues and track government responses.

## Features

- **Issue Reporting**: Citizens can report local problems with photos and location details
- **Real-time Tracking**: Monitor the status of reported issues and government responses
- **Government Dashboard**: Officials can manage and respond to citizen issues
- **Analytics**: Comprehensive insights into community issues and resolution rates
- **Multi-role Support**: Different interfaces for citizens, government officials, and administrators

## Tech Stack

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Linting**: ESLint
- **Development**: VS Code with recommended extensions

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn
- VS Code (recommended)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd stand-with-nepal
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### VS Code Setup

This project includes VS Code configuration for optimal development experience:

1. **Recommended Extensions**: Install the recommended extensions when prompted
2. **Debug Configuration**: Use F5 to launch Chrome with debugging support
3. **Tasks**: Use Ctrl+Shift+P → "Tasks: Run Task" to run build tasks
4. **Integrated Terminal**: Use Ctrl+` to open terminal and run commands

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### VS Code Commands

- **F5**: Launch Chrome with debugger attached
- **Ctrl+Shift+P → "Tasks: Run Build Task"**: Start development server
- **Ctrl+Shift+P → "Tasks: Run Task"**: Access all available tasks

## Project Structure

```
src/
├── components/          # React components
├── hooks/              # Custom React hooks
├── types/              # TypeScript type definitions
├── utils/              # Utility functions and constants
├── App.tsx             # Main application component
├── main.tsx            # Application entry point
└── index.css           # Global styles

.vscode/                # VS Code configuration
├── settings.json       # Editor settings
├── extensions.json     # Recommended extensions
├── launch.json         # Debug configuration
└── tasks.json          # Build tasks
```

## Development Workflow

1. **Start Development**: Press F5 or run `npm run dev`
2. **Make Changes**: Edit files in VS Code with full IntelliSense support
3. **Debug**: Set breakpoints and use Chrome DevTools integration
4. **Build**: Use Ctrl+Shift+P → "Tasks: Run Task" → "build"
5. **Lint**: Use Ctrl+Shift+P → "Tasks: Run Task" → "lint"

## User Roles

### Citizens
- Report issues with photos and location
- Track issue status and government responses
- Upvote and comment on community issues
- View analytics and trending issues

### Government Officials
- View and manage issues in their jurisdiction
- Update issue status and provide responses
- Assign issues to departments
- Track resolution metrics

### Administrators
- Manage user accounts and verifications
- Moderate content and handle reports
- View system-wide analytics
- Configure platform settings

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is licensed under the MIT License.