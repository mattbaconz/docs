# Plugin documentation by mattbaconz

Public Minecraft plugin guides, built with Mintlify. `docs.json` owns the navigation; each product has its own directory. Stonkz and WorldEvents use separate GitBook sites linked from the home page.

## Preview and check

With Node.js installed, run from this directory:

```powershell
npx mint dev --port 3000
npx mint broken-links
npx mint validate
```

Use an unused port if another preview is running. Check edited pages at desktop and mobile widths before publishing.

## Editing

Check commands, config keys and edition differences against the released plugin. Keep unreleased behavior out of installation instructions. Use title and description frontmatter on every MDX page, register new pages in `docs.json`, and keep internal links working.

Before changing a dirty file, preserve the existing edit. Repository instructions in `AGENTS.md` and the parent Minecraft workspace apply.

## Publishing

Pushing the default branch can deploy the public docs automatically. Prepare and verify the local changes, then obtain the required approval before pushing. A local preview is not a published update.
