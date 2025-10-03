# Base react scaffolding

This is a comprehensive React TypeScript application.

## 📋 Documentation

Comprehensive documentation is available in the `/src/docs/` directory:

- 

## 🛠️ Technical Stack

- **Frontend**: React 19.1.1 + TypeScript 5.8.3
- **Build Tool**: Vite 7.1.7
- **Testing**: Vitest 3.2.4 + Testing Library 16.3.0
- **Routing**: React Router DOM 7.9.3
- **Code Quality**: ESLint 9.36.0 + Prettier 3.6.2

## 📦 Installation & Setup

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Quick Start

1. **Clone and Install**

```bash
git clone <repository-url>
cd base-react-scaffolding
npm install
```

2. **Development Server**

```bash
npm run dev
```

Opens application at `http://localhost:5173`

3. **Build for Production**

```bash
npm run build
```

4. **Preview Production Build**

```bash
npm run preview
```

## 🔧 Available Scripts

### Development Scripts

```bash
# Start development server with hot reload
npm run dev

# Start development with verbose output
npm run dev -- --mode development
```

### Build Scripts

```bash
# Type check and build production bundle
npm run build

# Build with development dependencies
npm run build -- --mode development

# Preview built application
npm run preview
```

### Code Quality Scripts

```bash
# Run ESLint across all files
npm run lint

# Run linting with auto-fix
npm run lint -- --fix

# Type checking only
npx tsc --noEmit
```

### Testing Scripts

```bash
# Run all tests
npx vitest

# Run tests in watch mode
npx vitest --watch

# Run tests with coverage
npx vitest --coverage

# Run tests in CI mode
npx vitest --run
```

### Additional Development Scripts

```bash
# Format code with Prettier
npx prettier --write .

# Check code formatting
npx prettier --check .

# Clean build artifacts
rm -rf dist/

# Clean node modules and reinstall
rm -rf node_modules package-lock.json && npm install
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Route-based page components
├── hooks/              # Custom React hooks
├── context/            # React Context providers
├── utils/              # Utility functions and helpers
├── styles/             # Global styles and theme
├── docs/               # Project documentation
│   ├── use-cases.md    # Detailed use cases documentation
│   └── test-scenarios.md # Comprehensive test scenarios
└── assets/             # Static assets (images, icons, etc.)
```

## 🧪 Testing Strategy

### Test Coverage Areas

- **Unit Tests**: Individual component and hook testing
- **Integration Tests**: API integration and data flow
- **End-to-End Tests**: Complete conversion workflows

### Test Data Management

```bash
# Set up test environment
npm run test:setup

# Run all test suites
npm run test:all

# Run specific test categories
npm run test:unit
npm run test:integration
npm run test:e2e
```

## 🚀 Deployment Considerations

### Environment Configuration

```bash
# Development
npm run serve:dev

# Staging
npm run serve:staging

# Production
npm run serve:prod
```

## 🤝 Contributing

### Development Workflow

1. Create feature branch from `main`
2. Implement changes with tests
3. Run linting and formatting
4. Submit pull request for review

### Code Standards

- TypeScript strict mode enabled
- ESLint configuration enforced
- Prettier formatting standards
- Conventional commit messages

## 📞 Support

For technical questions or issues:

- Check documentation in `/src/docs/`

## 📄 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

---

_Built with ⚡ React + TypeScript + Vite for modern web development_
