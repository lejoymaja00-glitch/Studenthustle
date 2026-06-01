# Contributing to Student Hustle

We're excited that you want to contribute! 

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a feature branch
4. Make your changes
5. Submit a pull request

## Development Setup

```bash
npm install
cp .env.example .env.local
npx prisma db push
npm run dev
```

## Coding Standards

### TypeScript
- Use TypeScript for all files
- Define types for all functions
- Avoid `any` type

### React Components
- Use functional components with hooks
- Add 'use client' for client components
- Use PascalCase for component names
- Export as default

### File Naming
- Components: PascalCase.tsx
- Functions: camelCase.ts
- Constants: UPPER_SNAKE_CASE

## Git Workflow

### Branch Names
- Feature: `feature/description`
- Bug fix: `bugfix/description`
- Docs: `docs/description`

### Commit Messages
```
type: description

Details about the change
```

Types: feat, fix, docs, style, refactor, test, chore

## Pull Request Process

1. Update with latest main
2. Add descriptive title
3. Reference related issues
4. Request reviews
5. Address feedback
6. Get approval before merge

## Questions?

- Open a discussion
- Comment on issues
- Check documentation
- Ask the community

Thank you for contributing! 🙌
