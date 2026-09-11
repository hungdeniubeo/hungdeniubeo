# Repository Instructions

## Purpose

This repository is the GitHub profile repository for `hungdeniubeo`.
The primary artifact is `README.md`.

## README rules

- Preserve compatibility with GitHub Markdown rendering.
- Do not use JavaScript, custom CSS, hover effects, or unsupported HTML/CSS behavior.
- Prefer GitHub-compatible Markdown, HTML, SVG badges, and external dynamic SVG services.
- Keep the profile visually clean, compact, and responsive.
- Avoid oversized banners, excessive spacing, or repetitive sections.
- Keep visual style consistent across sections.

## Dynamic content

- Prefer GitHub-compatible dynamic SVGs for stats, typing effects, streaks,
  contribution animations, badges, and similar profile elements.
- Do not add external widgets that require client-side JavaScript.
- Verify image URLs and GitHub Actions paths when changing dynamic assets.

## Editing workflow

- For visual changes, inspect the current `README.md` structure before editing.
- Make targeted changes instead of rewriting the entire profile unless requested.
- Preserve existing working links, actions, and assets unless they are being replaced intentionally.
- When modifying GitHub Actions, inspect the related workflow file before changing references.

## Delivery

- After completing and validating a requested change, automatically commit the task-scoped changes and push the current branch to `origin` without asking again.
- Do not include unrelated worktree changes in the commit.
- Skip automatic commit or push when the user explicitly asks not to do it.
- Never force-push. If the remote has diverged, fetch and rebase safely; stop and report any conflict instead of overwriting remote work.

## Validation

- Check Markdown/HTML structure after edits.
- Check that referenced local files and workflow paths exist.
- Do not claim that remote SVGs or third-party services render correctly unless verified.
