# Operations Incident Lab

Git and GitHub hands-on training for DevOps.

## Branches
- main: Stable production configuration
- dev: Integration and testing
- feature/*: Configuration improvements
- hotfix/*: Emergency production changes

## Environments
- settings/staging.conf
- settings/production.conf

## Security
Never commit credentials or private keys.
Review staged changes before every commit.
Run secret scanning before publishing changes.
