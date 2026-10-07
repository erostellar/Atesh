# Project guidance

This project is the static Astro website for ATESH Grill & Restaurant in Bremen.

## Design and visual identity

- Preserve the existing visual identity and restaurant aesthetic.
- Do not redesign the site into a generic SaaS or template-like look.
- Reuse existing components, typography, spacing, colors, and interaction patterns where appropriate.
- Match the established dark brown backgrounds, gold and red accents, and DM Sans and Playfair Display typography.
- Before making larger visual changes, inspect the surrounding components and match the existing design language.

## Architecture and implementation

- Keep the site lightweight and static unless there is a strong reason not to.
- Prefer Astro-native solutions over adding frontend frameworks.
- Work within the existing organization: pages in `src/pages`, shared components in `src/components`, the shared layout in `src/layouts`, and global styles in `src/styles/global.css`.
- Maintain responsive behavior and accessibility, including keyboard navigation, focus handling, readable contrast, and appropriate semantic HTML.

## Git operations

- Do not run Git commands that modify repository state.
- Do not stage, commit, push, reset, checkout, merge, or rebase.
- The user handles all Git operations themselves.
