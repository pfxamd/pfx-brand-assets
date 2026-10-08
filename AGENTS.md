# PFxamd brand assets

This repository is a storage source for official PFxamd assets, not a runtime dependency.

When asked to use an official PFxamd asset in another project:
1. Read `brand.json` to find the current asset path.
2. Retrieve the file from this repository at that path.
3. Copy the exact file bytes into the target project's own asset directory.
4. Use the local project file, not a remote URL or runtime dependency.
5. Do not edit, recreate, or convert an asset unless explicitly instructed.
6. Do not assume an asset exists unless it appears in the repository.

The `AGENTS.md` in this repository applies when working in this repository; for work in another repository, the agent must be explicitly directed here or otherwise have these instructions available.
