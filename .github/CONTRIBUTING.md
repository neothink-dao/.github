# Contributing to Neothink

Welcome to the Neothink ecosystem! We're building AI-native applications and breakthrough thinking platforms supporting Mark Hamilton's philosophy-based personal development methodology.

## 🚀 Getting Started

### Prerequisites
- **Node.js 24.8.0+** with native TypeScript support
- **npm 10+** for package management
- **Git** for version control
- **Claude Code** (recommended) for AI-native development

### Development Environment Setup
```bash
# Clone the repository
git clone https://github.com/neothink-dao/[repository-name].git
cd [repository-name]

# Install dependencies
npm install

# Set up development environment
npm run dev
```

## 🏗️ Project Architecture

### Repository Structure
- **neothink.com**: Strategic research and planning hub
- **web**: Next.js 15.5 + React 19.1 implementation
- **supabase**: Production-ready backend with AI capabilities
- **mobile**: Cross-platform mobile application
- **admin**: Internal management and integration tools
- **neo-tech**: AI-native technology documentation

### Technology Stack
- **Frontend**: Next.js 15.5, React 19.1, TypeScript 5.9.2
- **AI Framework**: Vercel AI SDK 5.0 with multi-modal capabilities
- **Backend**: Supabase with pgvector, Edge Functions V2
- **Styling**: Tailwind CSS 4.x, shadcn/ui Platform
- **Testing**: Vitest 3.x, Playwright 1.55+, AI-enhanced testing

## 🤝 How to Contribute

### 1. Fork and Clone
```bash
# Fork the repository on GitHub
# Clone your fork
git clone https://github.com/your-username/[repository-name].git
cd [repository-name]

# Add upstream remote
git remote add upstream https://github.com/neothink-dao/[repository-name].git
```

### 2. Create a Feature Branch
```bash
# Create and switch to a new branch
git checkout -b feature/your-feature-name

# Or for bug fixes
git checkout -b fix/issue-description
```

### 3. Make Your Changes
- Follow the existing code style and conventions
- Write clear, descriptive commit messages
- Add tests for new functionality
- Update documentation as needed
- Ensure AI safety compliance

### 4. Test Your Changes
```bash
# Run all tests
npm test

# Run AI-specific tests
npm run test:ai

# Run end-to-end tests
npm run test:e2e

# Check types and linting
npm run type-check
npm run lint
```

### 5. Submit a Pull Request
```bash
# Push your changes
git push origin feature/your-feature-name

# Create a pull request on GitHub
# Fill out the PR template completely
```

## 📋 Contribution Guidelines

### Code Standards
- **TypeScript**: All new code must be TypeScript
- **ESLint**: Follow the configured ESLint rules
- **Prettier**: Use Prettier for code formatting
- **Naming**: Use descriptive, clear variable and function names
- **Comments**: Document complex logic and AI-specific implementations

### AI-Native Development
- **AI-First Design**: Consider AI agent orchestration in all features
- **Tool Generation**: Use MCP-to-AI-SDK for system integrations
- **Safety First**: Implement AI safety validation for all AI features
- **Performance**: Optimize for edge deployment and sub-second responses
- **Multi-modal**: Design for text, image, audio, and video inputs

### Commit Message Format
```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `ai`: AI/ML specific changes
- `security`: Security improvements

**Examples:**
```
feat(web): add AI-powered user onboarding flow
fix(supabase): resolve edge function timeout issues
ai(mobile): implement multi-modal content processing
docs(neo-tech): update AI development guidelines
```

### Pull Request Guidelines
- **Title**: Clear, descriptive title
- **Description**: Explain what and why, not just what
- **Testing**: Include test results and validation steps
- **Screenshots**: Add screenshots for UI changes
- **Breaking Changes**: Clearly document any breaking changes
- **AI Impact**: Describe AI-specific implications

### Code Review Process
1. **Automated Checks**: All CI/CD checks must pass
2. **Peer Review**: At least one team member review required
3. **AI Safety Review**: AI-related changes require safety validation
4. **Documentation Review**: Ensure documentation is updated
5. **Final Approval**: Core team member approval for merge

## 🔒 Security Considerations

### AI Security
- Never trust AI model outputs without validation
- Implement prompt injection protection
- Validate all AI-generated content
- Rate limit AI API calls
- Monitor for bias and harmful outputs

### Data Protection
- Follow privacy by design principles
- Implement proper data encryption
- Minimize data collection and retention
- Ensure GDPR compliance
- Protect personally identifiable information

### Code Security
- Regular dependency updates
- Security scanning in CI/CD
- Secure coding practices
- Input validation and sanitization
- Proper error handling

## 🎯 Community Platforms

### Primary Communities
- **Neothinkers**: Main community for breakthrough thinking
- **Ascenders**: Advanced acceleration and performance
- **Immortals**: Longevity and life extension focus

### Contribution Opportunities
- **Core Platform Development**: Next.js, React, AI features
- **AI Agent Development**: LangChain, agent orchestration
- **Community Features**: Real-time collaboration, social features
- **Mobile Development**: React Native, cross-platform
- **Backend Development**: Supabase, PostgreSQL, edge functions
- **Documentation**: Technical writing, tutorials, guides

## 🏆 Recognition

### Contributor Levels
- **Community Member**: First contribution merged
- **Regular Contributor**: 5+ contributions
- **Core Contributor**: 15+ contributions + technical leadership
- **Maintainer**: Trusted with repository maintenance

### Benefits
- **Recognition**: Public acknowledgment in project documentation
- **Early Access**: Preview features and beta testing opportunities
- **Community Perks**: Special access to community resources
- **Learning**: Direct mentorship and skill development

## 📞 Getting Help

### Development Support
- **GitHub Discussions**: General questions and discussions
- **Discord**: Real-time community chat
- **Email**: dev@neothink.com for technical questions

### AI Development
- **AI Safety**: ai-safety@neothink.com
- **Technical AI**: ai-dev@neothink.com
- **Model Integration**: models@neothink.com

### Community
- **General**: community@neothink.com
- **Platform Issues**: support@neothink.com
- **Partnerships**: partnerships@neothink.com

## 📚 Resources

### Documentation
- [AI-Native Development Guide](https://github.com/neothink-dao/neo-tech)
- [API Documentation](https://github.com/neothink-dao/supabase)
- [Component Library](https://github.com/neothink-dao/web)

### Learning
- [Breakthrough Thinking Methodology](https://github.com/neothink-dao/neothink.com)
- [AI Agent Development](https://github.com/neothink-dao/neo-tech)
- [Community Guidelines](https://github.com/neothink-dao/neothinkers)

---

**Thank you for contributing to the future of decentralized intelligence!**

*Building breakthrough thinking platforms with AI-native excellence.*