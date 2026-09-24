# RevenueFlow automatic publishing policy

This repository is the authoritative GitHub target for the RevenueFlow project.

## Required release workflow

For every verified RevenueFlow development version:

1. Complete the scoped implementation.
2. Run the required regression, static, security, and package checks.
3. Freeze the versioned source and documentation.
4. Build and verify the development ZIP/archive.
5. Commit and push the verified source to `main` automatically.
6. Record the version and archive SHA-256 in the final handoff.
7. If a GitHub push fails because of a conflict or repository-side error, repair the issue and retry before calling the version published.

Incomplete, partially tested, or timed-out development trees must not be pushed as completed releases.

The standing repository target is `sarwarrakib/RevenueFlow`.
