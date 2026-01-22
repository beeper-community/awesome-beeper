# Contributing to Awesome Beeper

Thank you for your interest in contributing to Awesome Beeper!

## How Contributions Work

This repository accepts contributions from two sources:

### Human Contributions

Community members are welcome to submit pull requests directly. Whether you have found a useful tool, written a guide, or discovered a new resource, your contributions help the entire Beeper community.

### Automated Contributions (beeper-scout)

[beeper-scout](https://github.com/beeper-community/beeper-scout) automatically discovers new Beeper-related projects and resources across GitHub, Matrix, and other platforms. When it finds something relevant, it creates a pull request here for review.

Automated PRs are clearly labeled and follow the same review process as human contributions.

---

## Submission Guidelines

### Adding a Resource

Please ensure your submission meets these criteria:

- **Search existing entries** before adding to avoid duplicates
- **Use the correct format**: `[Name](link) - Description.`
- **Keep descriptions concise** and end with a period
- **Add entries alphabetically** within their section
- **Verify the link works** and points to the correct resource
- **Check spelling and grammar**

### Categories

Add resources to the appropriate section:

| Category | What Belongs Here |
|----------|-------------------|
| **Official Resources** | Official Beeper websites, repositories, and documentation |
| **Bridges** | Protocol bridges and bridge libraries |
| **Clients** | Beeper clients and frontends |
| **Tools** | Utilities, monitoring tools, and integrations |
| **Guides** | Tutorials, how-to articles, and documentation |
| **Community** | Forums, chat rooms, and social links |

### Quality Standards

We accept resources that are:

- **Actively maintained** or still relevant
- **Working** and accessible
- **Valuable** to the Beeper community
- **Legal** and respectful of terms of service

---

## Pull Request Process

### For Humans

1. Fork the repository
2. Create a new branch: `git checkout -b add-resource-name`
3. Make your changes following the format guidelines
4. Commit with a descriptive message: `git commit -m "Add [resource name]"`
5. Push to your fork: `git push origin add-resource-name`
6. Open a pull request using the template

### For beeper-scout

Automated PRs follow this process:

1. Discovery system identifies new resource
2. AI analysis categorizes and scores relevance
3. PR is created with standardized format
4. Human reviewer approves or requests changes
5. Merge upon approval

---

## Review Process

All submissions go through review:

1. **Format check** - Follows style guidelines
2. **Link verification** - Resource is accessible
3. **Relevance check** - Appropriate for Beeper community
4. **Duplicate check** - Not already listed

PRs from beeper-scout include analysis metadata to help reviewers.

---

## Directory Structure

When adding guides or resources, use the appropriate directory:

```
awesome-beeper/
├── README.md           # Main curated list
├── CONTRIBUTING.md     # This file
├── guides/             # How-to articles and tutorials
│   └── README.md
└── resources/          # Categorized reference links
    └── README.md
```

---

## Questions?

- Open an issue if you are unsure about anything
- Join the [Beeper Community Matrix room](https://matrix.to/#/#beeper:beeper.com) for discussion
- Check [beeper-scout](https://github.com/beeper-community/beeper-scout) for discovery automation details

---

## Related Repositories

| Repository | Purpose |
|------------|---------|
| [beeper-pulse](https://github.com/beeper-community/beeper-pulse) | Notifications and alerts |
| [beeper-scout](https://github.com/beeper-community/beeper-scout) | Automated discovery |
| **awesome-beeper** | Curated documentation (this repo) |
