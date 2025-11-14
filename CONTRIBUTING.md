# Contributing Guidelines

Thank you for your interest in contributing to the Albanian Open Source Projects repository! This document provides guidelines and instructions for adding projects, suggesting improvements, and helping maintain this community resource.

---

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Adding a New Project](#adding-a-new-project)
- [Project Entry Format](#project-entry-format)
- [Quality Guidelines](#quality-guidelines)
- [Pull Request Process](#pull-request-process)
- [Issue Reporting](#issue-reporting)
- [Code of Conduct](#code-of-conduct)

---

## Ways to Contribute

You can contribute to this repository in several ways:

1. **Add new projects** - Share Albanian open source projects not yet listed
2. **Update existing entries** - Fix broken links, update statuses, or improve descriptions
3. **Improve documentation** - Enhance README sections, clarify instructions, or fix typos
4. **Translate content** - Help translate the repository to Albanian (Shqip)
5. **Curate and organize** - Suggest new categories or reorganize existing ones
6. **Spread the word** - Share this repository with Albanian developers and communities

---

## Adding a New Project

### Eligibility Criteria

Projects must meet **at least one** of the following criteria:

1. **Language Focus:** Project specifically supports or processes the Albanian language
2. **Geographic Focus:** Project relates to Kosovo, Albania, or Albanian-speaking regions
3. **Developer Origin:** Project created or primarily maintained by Albanian developers
4. **Cultural Relevance:** Project addresses Albanian cultural, social, or civic issues

### Additional Requirements

- **Open Source License:** Project must have an approved open source license (MIT, GPL, Apache, BSD, CC, etc.)
- **Public Repository:** Project must be publicly accessible (GitHub, GitLab, Bitbucket, Hugging Face, etc.)
- **Active or Significant:** Project should be either:
  - Currently active or maintained
  - Or historically significant to the Albanian open source community

---

## Project Entry Format

### Standard Format

Each project entry must follow this standardized format:

```markdown
### Project Name
**Description:** A concise 1-2 sentence description of what the project does and its purpose.
**Repository:** [Full URL to repository](https://full-url-here)
**Technology:** Primary technologies/languages used (e.g., Python, React, Machine Learning)
**Status:** Active | Maintained | Seeking Contributors | Historical
**Maintainer:** Name or organization
```

### Field Descriptions

- **Project Name:** Official name of the project (use title case)
- **Description:** Clear, concise explanation (1-2 sentences maximum). Avoid marketing language - focus on functionality
- **Repository:** Full clickable link to the project's repository or main website
- **Technology:** Key technologies, programming languages, or frameworks (comma-separated)
- **Status:**
  - **Active:** Regularly updated, commits within last 3-6 months
  - **Maintained:** Less frequent updates but still supported
  - **Seeking Contributors:** Project explicitly welcomes new contributors
  - **Historical:** No longer maintained but significant to the community
- **Maintainer:** Primary maintainer's name, GitHub username, or organization

### Example Entry

```markdown
### Albanian NLP Library
**Description:** A comprehensive library designed to enable Natural Language Processing tasks in the Albanian language, including tokenization, stemming, and text processing.
**Repository:** [github.com/arditdine/albanian-nlp](https://github.com/arditdine/albanian-nlp)
**Technology:** Python, NLP
**Status:** Active
**Maintainer:** Ardit Dine
```

---

## Quality Guidelines

### Description Guidelines

- **Be Concise:** 1-2 sentences maximum
- **Be Specific:** Clearly state what the project does
- **Avoid Jargon:** Write for a general technical audience
- **No Marketing Speak:** Focus on functionality, not promotional language
- **Professional Tone:** Maintain a neutral, informative tone

### Content Quality Standards

✅ **DO:**
- Verify links work before submitting
- Check that the project has an open source license
- Confirm the project meets eligibility criteria
- Use proper grammar and spelling
- Keep information factual and objective
- Place projects in the most appropriate category

❌ **DON'T:**
- Add proprietary or closed-source projects
- Include projects without clear Albanian connection
- Use superlatives or marketing language ("best," "revolutionary," "game-changing")
- Add broken or dead links
- Duplicate existing entries
- Include personal projects that aren't publicly available

### Categorization

Place your project in the **most appropriate** section:

- **Language & Linguistics:** NLP, translation, spell checkers, grammar tools, language learning
- **Web & Mobile Applications:** Websites, web apps, mobile apps, browser extensions
- **Tools & Utilities:** Developer tools, libraries, CLI tools, build systems
- **Documentation & Educational:** Tutorials, courses, documentation projects, curated lists
- **Infrastructure & DevOps:** Deployment tools, infrastructure projects, monitoring, CI/CD
- **Data & Research:** Datasets, research projects, data analysis tools, corpora
- **AI Models:** Machine learning models, language models, computer vision, speech recognition
- **Other Projects:** Projects that don't fit other categories, community organizations

If a project fits multiple categories, choose the **primary focus** or suggest creating a new category.

---

## Pull Request Process

### For GitHub Users

1. **Fork the repository** to your GitHub account

2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/albanian-opensource-projects.git
   cd albanian-opensource-projects
   ```

3. **Create a new branch** with a descriptive name:
   ```bash
   git checkout -b add-project-name
   # or
   git checkout -b update-section-name
   ```

4. **Make your changes** following the format guidelines above

5. **Test your changes:**
   - Verify all links work
   - Check Markdown formatting renders correctly
   - Ensure alphabetical ordering if applicable
   - Proofread for spelling and grammar

6. **Commit your changes** with a clear message:
   ```bash
   git add README.md
   git commit -m "Add Albanian NLP Library to Language & Linguistics section"
   ```

7. **Push to your fork:**
   ```bash
   git push origin add-project-name
   ```

8. **Create a Pull Request:**
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template with details about your addition
   - Submit the pull request

### Pull Request Template

When creating a pull request, please include:

```markdown
## Description
Brief description of what you're adding or changing.

## Project Added
- **Project Name:** [Name]
- **Category:** [Section name]
- **Albanian Connection:** [How this project relates to Albania/Albanian community]

## Checklist
- [ ] Project meets eligibility criteria
- [ ] Entry follows the standard format
- [ ] All links are working
- [ ] Project has an open source license
- [ ] Placed in appropriate category
- [ ] No duplicate entries
- [ ] Spelling and grammar checked
```

---

## Issue Reporting

### Types of Issues

You can open issues for:

1. **Suggesting Projects:** Recommend projects to add (if you can't submit a PR)
2. **Reporting Broken Links:** Alert us to dead or incorrect links
3. **Requesting Updates:** Notify us of outdated information
4. **Proposing Changes:** Suggest improvements to repository structure or documentation
5. **Asking Questions:** Ask about contribution process or project eligibility

### Issue Template

When opening an issue, please provide:

```markdown
## Issue Type
[Suggestion / Bug Report / Question / Enhancement]

## Description
Clear description of the issue or suggestion.

## Additional Context
Any relevant links, screenshots, or additional information.
```

### Alternative Contribution Methods

**Don't want to use GitHub?**
- **Email submissions:** Contact the maintainers via email with project details following the standard format
- **Social media:** Share project suggestions via Albanian developer communities
- **Community forums:** Post suggestions in Albanian tech forums or FLOSSK channels

---

## Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inclusive environment for all contributors, regardless of:
- Experience level
- Background or identity
- Geographic location
- Native language

### Expected Behavior

✅ **Please:**
- Be respectful and constructive in all interactions
- Welcome newcomers and help them contribute
- Focus on the quality and relevance of contributions
- Provide helpful feedback on pull requests and issues
- Respect differing viewpoints and experiences
- Accept constructive criticism gracefully

❌ **Do Not:**
- Use hostile, offensive, or discriminatory language
- Engage in personal attacks or trolling
- Spam or self-promote excessively
- Publish others' private information without permission

### Enforcement

Violations of the code of conduct may result in:
1. A warning from maintainers
2. Temporary ban from contributing
3. Permanent ban for severe or repeated violations

Report issues to the repository maintainers via private message or email.

---

## Review Process

### What to Expect

1. **Initial Review:** Maintainers will review your contribution within 3-7 days
2. **Feedback:** You may receive requests for changes or clarifications
3. **Approval:** Once approved, your contribution will be merged
4. **Recognition:** Contributors are credited in commit history

### Review Criteria

Maintainers will check:
- ✅ Meets eligibility criteria
- ✅ Follows format guidelines
- ✅ Contains accurate information
- ✅ Working links and proper citations
- ✅ Appropriate categorization
- ✅ No duplicates
- ✅ Quality of writing and presentation

---

## Translation Contributions

We welcome translations of this repository into Albanian (Shqip)!

### Translation Guidelines

- Maintain the same structure and formatting
- Keep technical terms consistent
- Preserve all links and references
- Create a new file: `README.sq.md` for Albanian version
- Update main README with link to translation

---

## Questions?

If you have questions about contributing:

1. Check existing issues for similar questions
2. Review this CONTRIBUTING.md document thoroughly
3. Open a new issue with the "question" label
4. Contact the maintainers directly
5. Join Albanian developer communities (FLOSSK, Open Labs, etc.)

---

## Recognition

All contributors are valued members of the Albanian open source community! Your contributions help:
- 🌍 Increase visibility of Albanian open source projects
- 🤝 Connect Albanian developers worldwide
- 📚 Provide resources for researchers and developers
- 🚀 Promote open source culture in Albania and Kosovo

Thank you for contributing!

---

**Maintained by the Albanian Open Source Community**
**License:** CC BY-SA 4.0
