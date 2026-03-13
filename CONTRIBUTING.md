# Contributing to Skill-Wanderer Organization Profile

Thank you for your interest in contributing to the Skill-Wanderer organization profile repository.
This repository powers the public organization profile and related documentation.

## Scope of This Repository

This repository is primarily for:

- Organization-level documentation and messaging.
- Profile content shown on GitHub (for example, `profile/README.md`).
- Supporting repository metadata files (for example, `README.md`, `LICENSE`, and this guide).

If your change is about application code, please contribute to the relevant project repository instead.

## Contribution Workflow

1. Choose your contribution path:

   - External contributors: fork the repository and clone your fork.
   - Long-term members: request direct collaborator access and work from an internal branch.

2. Fork path (external contributors):

   ```bash
   git clone https://github.com/yourusername/.github.git
   cd .github
   ```

3. Create a branch for your change:

   ```bash
   git checkout -b docs/short-change-summary
   ```

4. Make your updates and validate quality:

   - Keep wording clear, practical, and aligned with Skill-Wanderer values.
   - Verify links are valid and use `https`.
   - Ensure Markdown renders correctly in GitHub preview.

5. Commit with a descriptive message:

   ```bash
   git commit -m "docs: update profile messaging for clarity"
   ```

6. Push your branch and open a pull request to the `dev` branch first:

   ```bash
   git push origin docs/short-change-summary
   ```

## Long-Term Contribution

If you want to join as a long-term, committed member, contact the founder at quan.nguyen@skill-wanderer.com.

Long-term contributors may be invited as repository collaborators (as with some existing contributors) and can create branches directly in the repository before opening a pull request to `dev`.

## Pull Request Guidelines

- Keep pull requests focused on a single topic.
- Explain what changed, why it changed, and any impact on public-facing messaging.
- Include screenshots when changing content where rendered output matters.
- Update related files together when needed (for example, both `README.md` and `profile/README.md`).
- Open pull requests against the `dev` branch first unless maintainers explicitly request a different target.
- Every pull request is reviewed in two stages before merge: AI review first, then review by a senior team member.

## Style Expectations

- Prefer concise, plain English.
- Keep tone professional, practical, and education-first.
- Avoid promotional or unverifiable claims.
- Preserve existing structure and headings unless there is a strong reason to change them.

## Code of Conduct

By participating, you agree to collaborate respectfully and constructively.

## License

All Skill-Wanderer organization repositories are licensed under the Apache License 2.0 unless explicitly stated otherwise.

By contributing to this repository, you agree that your contributions are licensed under the repository's [Apache License 2.0](LICENSE).