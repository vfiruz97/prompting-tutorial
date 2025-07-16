# AI Prompt Engineering Guide

A simple 5-step strategy for effective AI-assisted coding.

## The 5-Step Process

### 1. 📚 Teach AI Your Project

Create comprehensive project documentation:

- **Project Overview**: Goals, audience, and purpose
- **Structure**: Architecture and component relationships
- **Tech Stack**: Languages, frameworks, and tools
- **Guidelines**: Coding standards and conventions

Store these files in your repository and reference them in every AI prompt.

**Example Prompts:**

```
Create a "project_overview.md" file describing this project's structure, folder purposes, and key files. Focus on learning the repository first - don't create files yet.
```

```
Explore the entire repository to understand the codebase from multiple angles: as a software architect, a software engineer, and a product manager. Compile your findings into a comprehensive Markdown document in the root directory. Use Mermaid diagrams for technical concepts.
```

```
Analyze this codebase and create a technical architecture document that includes: project goals, target audience, folder structure with purposes, key dependencies, coding standards used, and any architectural patterns. Don't modify any files yet - just learn and document.
```

### 2. 📋 Analyze Requirements

Break down tasks into manageable components using Product Requirements Documents (PRDs).

**Example Prompts:**

```
Create a PRD for [feature description]. Think deeply about requirements and implementation details. Don't code yet - just create the PRD markdown file.
```

```
I want you to act as a product manager and create a PRD for [feature description]. What steps do we have to take to implement this feature? Include user stories, technical requirements, acceptance criteria, and potential challenges. Don't code yet.
```

```
Create a comprehensive PRD for [feature description] that includes: problem statement, user personas, functional requirements, non-functional requirements, technical architecture decisions, implementation phases, and success metrics. Break down the implementation into clear, actionable steps.
```

```
Analyze [feature description] and create a PRD that answers: What problem does this solve? Who are the users? What are the core functionalities? What are the technical constraints? What is the implementation roadmap? Present this as a structured markdown document.
```

Store PRDs as: `prds/000-feature_name.md`

### 3. 💻 Prompt AI to Code

With clear project understanding and requirements, give specific coding instructions.

**Example Prompt:**

```
Fully implement this PRD.
```

### 4. 🔍 Review and Test

- Review generated code
- Test functionality
- Use Git for version control
- Iterate and refine as needed
- Prefer familiar packages and libraries

### 5. 📝 Update Documentation

Keep documentation current with code changes.

**Example Prompts:**

```
Update the PRD to reflect the implemented changes.
```

```
Update the project overview with new structure changes and technologies.
```

## Key Benefits

- **Consistency**: Standardized approach across projects
- **Quality**: Systematic review and testing
- **Maintainability**: Up-to-date documentation
- **Efficiency**: Clear process reduces back-and-forth

## Quick Start

1. Document your project structure
2. Create a PRD for your feature
3. Ask AI to implement it
4. Review, test, and iterate
5. Update your documentation

---

_Mastering prompt engineering unlocks the full potential of AI coding assistants._
