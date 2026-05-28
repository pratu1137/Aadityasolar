# Contributing to Aadityasolar

First off, thank you for considering contributing to Aadityasolar! It's people like you that make Aadityasolar such a great platform.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

**Before Creating a Bug Report**
- Check the [issues](https://github.com/pratu1137/Aadityasolar/issues) list to ensure the bug hasn't already been reported
- If you find a closed issue that relates to your problem, open a new issue and include a link to the original issue

**How Do I Submit A (Good) Bug Report?**

Bugs are tracked as [GitHub issues](https://github.com/pratu1137/Aadityasolar/issues). Create an issue and provide the following information:

- **Use a clear and descriptive title** for the issue
- **Describe the exact steps which reproduce the problem** in as many details as possible
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps** and point out what's wrong
- **Explain which behavior you expected to see instead and why**
- **Include screenshots and animated GIFs if possible**

### Suggesting Enhancements

**Before Suggesting an Enhancement**
- Check if the enhancement has already been suggested in the [issues](https://github.com/pratu1137/Aadityasolar/issues)

**How Do I Submit A (Good) Enhancement Suggestion?**

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Explain why this enhancement would be useful**

### Pull Requests

- Fill in the required template
- Follow the TypeScript and code style guidelines
- Include appropriate test cases
- Document your changes in the README if needed
- End all files with a newline

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

### TypeScript Styleguide

- Use TypeScript for all new code
- Prefer `const` over `let`, avoid `var`
- Use meaningful variable names
- Add type annotations for function parameters and return types
- Use interfaces for object types when possible
- Keep functions small and focused

### CSS/Tailwind Styleguide

- Use Tailwind CSS utility classes
- Follow the atomic CSS approach
- Use Tailwind's theme for colors and spacing
- Keep custom CSS to a minimum

### React Styleguide

- Use functional components with hooks
- Keep components small and focused
- Use meaningful prop names
- Document complex components with JSDoc comments
- Avoid prop drilling (use context when necessary)

## Setting Up Your Development Environment

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/Aadityasolar.git`
3. Navigate to the project: `cd Aadityasolar`
4. Install dependencies: `pnpm install`
5. Create a feature branch: `git checkout -b feature/your-feature`
6. Make your changes
7. Test your changes: `pnpm typecheck && pnpm build`
8. Commit your changes: `git commit -am 'Add new feature'`
9. Push to the branch: `git push origin feature/your-feature`
10. Submit a pull request

## Additional Notes

- This is a monorepo using pnpm workspaces
- Always use `pnpm` instead of npm or yarn
- Ensure type checking passes before submitting PR
- Keep PRs focused on a single feature or fix

Thank you for contributing! 🎉
