# Contributing to Shopify Snippets Hub

Thank you for considering contributing! We welcome improvements, new snippets, and bug fixes.

## How to Contribute

1. **Fork** the repository and **create your branch** (`git checkout -b feature/my-snippet`).
2. **Add** your snippet file under the appropriate folder:
   - Full sections → `/sections/`
   - Stand-alone snippets → `/snippets/`
   - Utilities or docs → `/utilities/`
3. **Document** your snippet:
   - Include a header block in your snippet file with:
     ```liquid
     {%- comment -%}
     Title: [Short title]
     Description: [What it does]
     Usage: [Code or include example]
     Compatibility: [Any theme/version notes]
     {%- endcomment -%}
     ```
4. **Ensure** your code is:
   - Theme-agnostic
   - Well-formatted and commented
   - Tested on a development theme
5. **Commit** your changes (`git commit -m "Add [snippet name]"`).
6. **Push** to your fork and **open a Pull Request** against `main`.
7. Fill out the PR form, describing your changes, testing steps, and any screenshots.

## Code Style

- Use [Prettier](https://prettier.io/) for formatting.
- Follow Liquid best practices (minimize `if` nesting, use `assign` and `render` where appropriate).
- Keep CSS utilities in `/utilities/` for shared use.

## Seeking Help

If you need assistance or want a custom snippet:
- **Open an issue** with the “help wanted” label.
- Provide details: theme, context, desired behavior.

Thank you for making this project better!  
