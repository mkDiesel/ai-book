# Research: Docusaurus Setup and Best Practices

This document summarizes the research for setting up the Docusaurus framework for the "Physical AI & Humanoid Robotics" course.

## Docusaurus Project Structure

**Decision**: We will use the standard Docusaurus `classic` template structure.

**Rationale**: The classic template provides a well-organized structure that is easy to understand and maintain. It includes directories for documentation (`docs`), blog (`blog`), custom pages (`src/pages`), and static assets (`static`), which is sufficient for our needs.

**Alternatives considered**: A custom structure was considered but rejected as it would add unnecessary complexity.

**Key structural elements**:
- `docs/`: Contains the course content as Markdown files.
- `src/pages/`: Can be used for custom pages like a landing page or about page.
- `docusaurus.config.js`: Main configuration file for the site.
- `sidebars.js`: To define the navigation sidebar for the course content.

## Embedding Code Examples

**Decision**: We will use standard Markdown fenced code blocks with Prism for syntax highlighting. For more complex examples, especially in the "AI Agents & ROS 2 Integration" chapter, we will consider using the `@docusaurus/theme-live-codeblock` plugin to provide a live interactive editor. For multi-language examples (e.g. Python and C++), we will use the `Tabs` component.

**Rationale**: This approach provides a good balance between simplicity and interactivity. Standard code blocks are easy to write and maintain, while the live code editor can enhance the learning experience for coding-heavy sections.

**Alternatives considered**:
- Using only static code blocks was considered for simplicity, but rejected as it would be less engaging for the coding-focused chapters.
- Using an external service like CodeSandbox was considered but rejected to keep the documentation self-contained.

**Best Practices to Follow**:
- Use language identifiers for syntax highlighting (e.g., `python`, `cpp`, `xml`).
- Use line highlighting to draw attention to specific parts of the code.
- Add titles to code blocks to indicate the file name or context.
