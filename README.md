# USAFacts Github Workflows
We use shareable Github Workflows to minimize duplicate code across our many repositories.

## Rules for all workflows:
1. Must not contain any secrets / private information. (This repo is public)
2. All workflows must be passed secrets from their caller. Do not rely on Org or Project secrets. (The caller can pass through Org/Project secrets as needed)
3. Consider the confidential nature of the code you are pushing here. (THIS REPO IS PUBLIC!)

# Environments
## Frontend
### Frontend Libraries
1. Copy `frontend/library/*.yml` into `<your repo>/.github/workflows/`
2. Copy `frontend/npm-autoupdate-minor.yml` into `<your repo>/.github/workflows/`

### Frontend CJS Libraries
1. Copy `frontend/library-cjs/*.yml` into `<your repo>/.github/workflows/`
2. Copy `frontend/npm-autoupdate-minor.yml` into `<your repo>/.github/workflows/`

### Frontend Apps
1. Copy `frontend/app-*.yml` into `<your repo>/.github/workflows/`
2. Copy `frontend/npm-autoupdate-minor.yml` into `<your repo>/.github/workflows/`

## Backend
### Backend Libraries
1. Copy `backend/library/*.yml` into `<your repo>/.github/workflows/`

### Backend Services
1. Copy `backend/service/*.yml` into `<your repo>/.github/workflows/`

## Data
