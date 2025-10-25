# poc-release-please

This is a proof of concept repository to demonstrate the use of release-please with multiple release branches (alpha and beta).

The repository contains two release branches:
- `alpha`: This branch is for the alpha releases.
- `beta`: This branch is for the beta releases.

The `release-please` GitHub Action is configured to create releases for both branches based on the commits made to each branch.

## Usage

To trigger a release, simply push commits to either the `alpha` or `beta` branch. The `release-please` action will automatically create a new release based on the commit messages.

## Configuration

The `release-please` action is configured in the `.github/workflows/release-please.yml` file. You can customize the configuration to suit your needs.