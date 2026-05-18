# C# Interview & Assessment Bootcamp (Unity Developer Edition)

## Purpose

This 4-week bootcamp is designed for Unity/game developers who already know C# syntax but need stronger general-purpose .NET engineering skills for:

- Technical interviews
- Online coding assessments
- Take-home assignments
- Backend/tools engineering roles
- Pure C# problem solving outside Unity

Unity teaches practical gameplay scripting, but interviews often evaluate areas Unity workflows rarely emphasize:

- Core language fluency
- Collections and algorithms
- Interfaces and architecture
- Dependency injection
- Async/await
- LINQ
- Unit testing
- Clean project structure

This bootcamp focuses on building those skills with small, realistic projects using plain .NET.

---

# Time Commitment

Recommended:
- 2–3 hours/day
- 5 days/week
- 4 weeks total

Minimum:
- 90 minutes/day consistently

---

# Core Rules & Standards

These rules apply to every project in the bootcamp.

## General Standards

- Use .NET 8
- Use console applications only
- Use Git from Day 1
- Commit after every meaningful milestone
- Enable nullable reference types
- Prefer composition over inheritance
- Avoid static mutable state
- Keep methods small and focused
- Use meaningful naming
- Use constructor injection
- Prefer interfaces for service boundaries
- Separate business logic from I/O
- Every project should build cleanly with zero warnings

---

# Folder Structure Standard

Use this structure for every project:

```text
project-name/
  src/
    ProjectName.App/
    ProjectName.Core/
  tests/
    ProjectName.Tests/
  README.md
