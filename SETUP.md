# Setup Guide

This package is designed for the GitHub profile repository:

`aahana-gupta-ai/aahana-gupta-ai`

## Files

```text
README.md
assets/
  header.svg
  research-map.svg
  footer.svg
.github/
  workflows/
    snake.yml
```

## Upload

1. Open the `aahana-gupta-ai/aahana-gupta-ai` repository.
2. Replace the current root `README.md` with the included `README.md`.
3. Upload the entire `assets` folder.
4. Upload `.github/workflows/snake.yml` while preserving the folder structure.
5. Commit the changes to the default branch.

## Activate the contribution snake

After the files are uploaded:

1. Open the repository's **Actions** tab.
2. Select **Generate contribution snake**.
3. Click **Run workflow**.
4. Wait for the workflow to finish.
5. Refresh the profile README.

The workflow publishes two SVG files to an `output` branch:

- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg`

The README already points to these files.

## GitHub Actions permission

If the workflow cannot push the `output` branch:

1. Repository **Settings**
2. **Actions → General**
3. Under **Workflow permissions**, choose **Read and write permissions**
4. Save
5. Run the workflow again

## Dynamic graph services used

The README uses public profile-card services for:

- GitHub stats
- top languages
- commit streak
- contribution activity graph
- profile summary cards
- GitHub trophies
- repository cards

These images are generated dynamically from the public GitHub account. They do not need manual updating.

## Important

The professional profile content is written for **Aahana Gupta**, while the GitHub username used by the graph URLs is **aahana-gupta-ai** because that is the profile repository supplied for this package.

If the profile is later moved to a different GitHub username, replace every occurrence of `aahana-gupta-ai` in `README.md`.
