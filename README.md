# Claude Building Blog Skill

A workflow skill for adding a blog to a Next.js website using Sanity CMS. It focuses on an SEO-first, internationalization-ready, accessible, and performance-conscious editorial experience.

## What It Covers

- **Project reconnaissance:** Inspect the existing Next.js project, routing, dependencies, i18n, design tokens, analytics, and existing Sanity setup before making changes.
- **Requirements intake:** Use the technical requirements reference to collect project-specific editorial and technical decisions.
- **Architecture planning:** Define the blog scope, phases, constraints, and open decisions before implementation.
- **Sanity integration:** Structure the blog around Sanity as the editorial content platform.
- **SEO and performance:** Follow the requirements specification for search visibility, performance budgets, and accessibility.
- **Internationalization:** Account for the host project's locale and routing conventions.
- **Hero imagery:** Use the image style guide when AI-generated blog hero images are in scope.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-building-blog-skill.git ~/.claude/skills/building-blog
```

## Using the Skill

Example request:

```text
Use the building-blog skill to add a Sanity-powered blog to this
Next.js project. Inspect the existing architecture first, gather
requirements, and prepare a plan for approval before coding.
```

## Supporting Files

The skill relies on two reference documents:

- `blog-technical-requirements.md` contains the intake questionnaire, project profile, technical specification, and pass/fail checklist.
- `blog-image-style-guide.md` provides the template for consistent AI-generated blog hero imagery.

[SKILL.md](SKILL.md) is the workflow orchestrator. Use project-local copies of the references to record project-specific answers rather than changing the universal source templates.

## Important Workflow Rule

The skill requires an approved high-level plan before implementation. It also specifies cases where a different solution is more appropriate, such as static MDX blogs, documentation sites, and high-velocity news publishers.
