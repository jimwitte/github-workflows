# GitHub Workflows
Centralized repository for reusable GitHub Actions workflows. Add calling workflow to projects as appropriate.

## Workflows
- **docker-publish.yml**: Builds and pushes Docker images to GitHub Container Registry (GHCR).

## Calling Workflows
- **call-docker-publish.yml**: `wget -P .github/workflows https://raw.githubusercontent.com/jimwitte/github-workflows/refs/heads/main/call-docker-publish.yml`
