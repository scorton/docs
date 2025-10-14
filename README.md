# Scorton

This repository contains the comprehensive documentation for SchoolyAI by Scorton, an AI-powered trust as a service platform that revolutionizes the way students learn and educators teach.

## Overview

 Scorton combines cutting-edge artificial intelligence with proven educational methodologies to create personalized learning experiences. Our platform offers:

- **AI-Powered Learning**: Personalized learning paths for each student
- **Comprehensive Course Management**: Create, organize, and deliver educational content
- **Progress Tracking**: Detailed analytics and insights into student performance
- **API Integration**: Robust APIs for seamless platform integration
- **Real-time Collaboration**: Interactive features for educators and students

## Documentation Structure

```
docs/
├── index.mdx              # Main landing page
├── quickstart.mdx         # Getting started guide
├── development.mdx        # Development setup
├── api-reference/         # API documentation
│   ├── introduction.mdx   # API overview
│   ├── endpoint/          # Individual endpoint docs
│   └── openapi.json      # OpenAPI specification
├── essentials/           # Core concepts and guides
└── images/              # Documentation assets
```

## Development

### Prerequisites

- Node.js (version 18 or higher)
- Git

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SchoolyAI/docs.git
   cd docs
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **View the documentation** at `http://localhost:3000`

### Documentation Development

To preview documentation changes locally:

```bash
npm run docs:dev
```

This will start the documentation server at `http://localhost:3001`.

## Contributing

We welcome contributions to improve our documentation! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes** and commit them: `git commit -m 'Add your feature'`
4. **Push to the branch**: `git push origin feature/your-feature-name`
5. **Submit a pull request**

### Documentation Guidelines

- Use clear, concise language
- Include code examples where appropriate
- Follow the existing documentation structure
- Test all links and code snippets
- Update the table of contents when adding new pages

## Deployment

Documentation is automatically deployed when changes are pushed to the main branch. The deployment process includes:

- Building the documentation
- Running link validation
- Deploying to our CDN
- Updating the live site

## Support

- **Documentation Issues**: Report problems with the documentation on [GitHub Issues](https://github.com/SchoolyAI/docs/issues)
- **Platform Support**: Contact our support team at support@schoolyai.com
- **Community**: Join our [GitHub Discussions](https://github.com/SchoolyAI/scorton-doc/discussions)

## License

This documentation is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

- **Live Documentation**: [docs.schoolyai.com](https://docs.schoolyai.com)
- **Main Platform**: [schoolyai.com](https://schoolyai.com)
- **API Dashboard**: [dashboard.schoolyai.com](https://dashboard.schoolyai.com)
- **GitHub Organization**: [github.com/SchoolyAI](https://github.com/SchoolyAI)
