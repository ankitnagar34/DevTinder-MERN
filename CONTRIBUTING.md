# Contributing to DevTinder

Thank you for your interest in contributing to DevTinder! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- MongoDB Atlas account
- Git
- Basic knowledge of React, Express.js, and MongoDB

### Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/yourusername/devtinder.git
   cd devtinder
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables (see README.md)
5. Start development servers:
   ```bash
   npm run dev
   ```

## 📋 Code of Conduct

- Be respectful and inclusive
- Follow professional communication standards
- Help maintain a welcoming environment for all contributors
- Report any unacceptable behavior to the maintainers

## 🛠 Development Guidelines

### Code Style
- Use ESLint configuration provided
- Follow existing code patterns
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused

### Commit Messages
Follow conventional commit format:
```
type(scope): description

- feat: new feature
- fix: bug fix
- docs: documentation changes
- style: formatting changes
- refactor: code refactoring
- test: adding tests
- chore: maintenance tasks
```

Examples:
```
feat(auth): add Google OAuth integration
fix(chat): resolve message ordering issue
docs(readme): update installation instructions
```

### Branch Naming
- Feature branches: `feature/description`
- Bug fixes: `fix/description`
- Documentation: `docs/description`
- Hotfixes: `hotfix/description`

### Pull Request Process

1. Create a feature branch from `main`
2. Make your changes with clear, descriptive commits
3. Update documentation if needed
4. Test your changes thoroughly
5. Submit a pull request with:
   - Clear title and description
   - Reference any related issues
   - Screenshots for UI changes
   - List of changes made

### Testing
- Test your changes locally before submitting
- Ensure both frontend and backend work correctly
- Test authentication flows
- Verify real-time features (chat, notifications)
- Check responsive design on mobile devices

## 📂 Project Structure

### Backend (`apps/backend/`)
```
src/
├── app.js              # Main application
├── config/             # Database configuration
├── middlewares/        # Custom middleware
├── models/            # Mongoose models
├── routes/            # API endpoints
└── utils/             # Helper functions
```

### Frontend (`apps/frontend/`)
```
src/
├── Components/        # React components
├── utils/            # Redux store & utilities
├── App.jsx           # Main application
└── main.jsx          # Entry point
```

## 🔧 Common Tasks

### Adding a New API Endpoint
1. Create route handler in `apps/backend/src/routes/`
2. Add middleware if needed
3. Update API documentation
4. Test with frontend integration

### Adding a New React Component
1. Create component in `apps/frontend/src/Components/`
2. Follow existing component patterns
3. Add proper prop types if using TypeScript
4. Ensure responsive design
5. Test across different screen sizes

### Database Changes
1. Update Mongoose models in `apps/backend/src/models/`
2. Add validation rules
3. Update seed data if necessary
4. Test database operations

## 🐛 Bug Reports

When reporting bugs, please include:
- Clear description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Screenshots or error messages
- Browser/environment information
- Relevant console logs

## 💡 Feature Requests

For new features:
- Check existing issues first
- Describe the feature clearly
- Explain the use case and benefits
- Consider implementation complexity
- Discuss with maintainers before starting work

## 🔄 Release Process

1. Features are merged to `develop` branch
2. Testing and integration on `develop`
3. Release candidates created from `develop`
4. Production releases merged to `main`
5. Releases are tagged with semantic versioning

## 📚 Resources

- [React Documentation](https://react.dev/)
- [Express.js Guide](https://expressjs.com/)
- [MongoDB Manual](https://docs.mongodb.com/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [Socket.IO Documentation](https://socket.io/docs/)

## 🎯 Areas for Contribution

We welcome contributions in these areas:
- **Frontend**: UI/UX improvements, new features
- **Backend**: API enhancements, performance optimization
- **Documentation**: Tutorials, guides, API docs
- **Testing**: Unit tests, integration tests
- **DevOps**: Deployment, monitoring, CI/CD
- **Security**: Security audits, vulnerability fixes

## 🏆 Recognition

Contributors will be:
- Listed in the README.md
- Mentioned in release notes
- Given credit in commit history
- Invited to join the core team for significant contributions

## 📞 Getting Help

- **Discord**: [Join our community](https://discord.gg/devtinder)
- **GitHub Discussions**: Ask questions and share ideas
- **Issues**: Report bugs and request features
- **Email**: contribute@devtinder.com

Thank you for contributing to DevTinder! 🚀
