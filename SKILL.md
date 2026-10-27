---
name: fastapi
description: Expert documentation and guidance for the FastAPI framework. Trigger this skill whenever the user asks about FastAPI features, tutorials, implementation details, or needs help with FastAPI code. This skill provides access to the full official documentation with resolved code examples.
---

# FastAPI Expert Skill

This skill provides expert guidance on the FastAPI framework using the official documentation.

## How to use

The documentation is organized in the `references/` directory. When a user asks a question, identify the relevant section and read the corresponding file.

### Documentation Map

- **Tutorial - User Guide**: `references/tutorial/`
  - Start with `references/tutorial/index.md` or `references/tutorial/first-steps.md`.
- **Advanced User Guide**: `references/advanced/`
  - Advanced features like WebSockets, Custom Responses, and Events.
- **Learn / Introduction**: 
  - `references/python-types.md` (Python Type Hints)
  - `references/async.md` (Async / Await)
- **Deployment**: `references/deployment/`
- **How-To / Recipes**: `references/how-to/`
- **API Reference**: `references/reference/`
- **Release Notes**: `references/release-notes.md`

## Principles

1. **Check the Docs First**: Always look for the relevant documentation page before answering. The files in `references/` have been processed to include actual code examples.
2. **Follow FastAPI Best Practices**: FastAPI relies heavily on Python type hints and Pydantic. Ensure all code examples follow these patterns.
3. **Async by Default**: Use `async def` for path operations unless there's a specific reason not to (e.g., blocking I/O without an async library).
4. **Interactive Docs**: Remind users that FastAPI automatically generates Swagger UI (`/docs`) and ReDoc (`/redoc`).

## Reference Navigation

If unsure where to look, start with `references/index.md` or use `grep` to search within the `references/` directory for specific keywords.
