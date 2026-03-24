# Contributing to awesome-ai-video-generation

Thank you for your interest in contributing to awesome-ai-video-generation! This curated list helps creators and developers discover the best AI-powered video generation tools, models, and resources. Your contributions make this resource more valuable for the community.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Style Guide](#style-guide)
- [Review Process](#review-process)

## Code of Conduct

This project and everyone participating in it is governed by our commitment to:

- **Be respectful**: Treat everyone with respect. Healthy debate is encouraged, but harassment is not tolerated.
- **Be constructive**: Provide constructive feedback and be open to receiving it.
- **Be inclusive**: Welcome newcomers and help them get started.

## How Can I Contribute?

### Reporting Issues

If you find a broken link, outdated information, or have a suggestion:

1. Check if the issue already exists
2. Open a new issue with a clear title and description
3. Include relevant links and context

### Adding New Items

Before submitting a new AI video generation tool or resource:

1. **Check if it's already listed** - Search the existing list first
2. **Ensure it meets quality standards**:
   - Active development or maintained status
   - Clear documentation or examples
   - Working demo or trial available (preferred)
   - Unique capabilities (not a duplicate of existing tools)
3. **Verify the link works** - Test all URLs before submitting

### Improving Documentation

- Fix typos and grammatical errors
- Improve descriptions for clarity
- Add usage examples where helpful
- Update outdated information

## Submission Guidelines

### Pull Request Process

1. **Fork the repository** and create your branch from `main`:
   ```bash
   git checkout -b add/my-awesome-tool
   ```

2. **Add your item** following the style guide below

3. **Update the Table of Contents** if adding a new category

4. **Commit your changes** with a clear message:
   ```bash
   git commit -m "Add: [Tool Name] - [Brief description]"
   ```

5. **Push to your fork**:
   ```bash
   git push origin add/my-awesome-tool
   ```

6. **Open a Pull Request** with:
   - Clear title describing what you're adding
   - Description explaining why the tool/resource is valuable
   - Link to the project's repository or website
   - Any relevant context or usage notes

### PR Title Format

- Adding a tool: `Add: [Tool Name] - [One-line description]`
- Adding a resource: `Add: [Resource Name] to [Category]`
- Fixing a link: `Fix: Update broken link for [Tool Name]`
- Documentation: `Docs: [Description of change]`

## Style Guide

### List Item Format

```markdown
- **[Tool Name](link)** - Brief description (max 15 words). `Model/Platform` `License`
```

Example:
```markdown
- **[Runway Gen-2](https://runwayml.com)** - Text-to-video generation with high fidelity results. `Diffusion` `Commercial`
```

### Category Organization

- Place items in the most relevant category
- Keep categories alphabetically sorted
- Within categories, items can be sorted by popularity or alphabetically
- Use subcategories for large sections (10+ items)

### Description Guidelines

- **Be concise**: Maximum 15 words
- **Be specific**: What does it do? What's unique about it?
- **Avoid hype**: No "best", "amazing", "revolutionary" - let the tool speak for itself
- **Include key info**: Model type, platform, or license when relevant

### Link Format

- Use HTTPS links when available
- Link to the main project page or repository
- For GitHub repos, use the repository URL (not the org page)

### Badges and Icons

Optional badges can be added after the description:

```markdown
- **[Tool Name](link)** - Description. ![Stars](https://img.shields.io/github/stars/user/repo)
```

## Review Process

### What We Look For

1. **Relevance**: Is it related to AI video generation?
2. **Quality**: Is it well-documented and maintained?
3. **Uniqueness**: Does it offer something different from existing items?
4. **Accessibility**: Is there a demo, trial, or free tier available?
5. **Accuracy**: Are links working and descriptions correct?

### Timeline

- Initial review: 3-5 business days
- Feedback incorporation: 1-2 iterations typical
- Merge: After approval from a maintainer

### Common Reasons for Rejection

- Duplicate of existing item
- Broken or inaccessible links
- Insufficient documentation
- Not actively maintained
- No demo or trial available (unless exceptional value)
- Description is too long or promotional

## Development Setup

### Local Testing

To preview your changes locally:

1. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/awesome-ai-video-generation.git
   cd awesome-ai-video-generation
   ```

2. Install markdown linter (optional but recommended):
   ```bash
   npm install -g markdownlint-cli
   markdownlint README.md
   ```

3. Check all links (optional):
   ```bash
   npm install -g markdown-link-check
   markdown-link-check README.md
   ```

## Questions?

- Open an issue for general questions
- Comment on an existing issue or PR for specific discussions
- Check closed issues/PRs for similar past discussions

## Recognition

Contributors will be:
- Listed in the repository's contributor graph
- Acknowledged in release notes for significant contributions
- Eligible for RustChain RTC bounties where applicable

---

Thank you for helping make awesome-ai-video-generation a valuable resource for the AI video generation community! 🎬
