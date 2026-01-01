# Data Model

This document defines the data model for the "Physical AI & Humanoid Robotics" course.

## Entities

### Module

Represents a collection of chapters.

**Fields**:
- `title` (string): The title of the module.
- `description` (string): A brief description of the module.
- `chapters` (array of Chapter): The chapters that belong to the module.

### Chapter

Represents a single chapter in the course.

**Fields**:
- `title` (string): The title of the chapter.
- `content` (string): The content of the chapter in Markdown format.

## Relationships

- A `Module` has a one-to-many relationship with `Chapter`.
- A `Chapter` belongs to exactly one `Module`.

## Validation Rules

- `Module.title` is mandatory.
- `Chapter.title` is mandatory.
