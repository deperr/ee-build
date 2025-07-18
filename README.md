# ee-build
A repository for the automated builds of execution environments using GitHub actions.

## GitHub Repository Configuration

Set the following variables within the GitHub repository itself.

### Repository Secrets

- `REDHAT_USER`
- `REDHAT_PASSWORD`
- `QUAY_USER`
- 'QUAY_REPO'
- `QUAY_PASSWORD`

### Repository Variables

- `IMAGE_NAME`

## Quay Container Registry Prerequisites

- Configure a Robot Account
    - Navigate to your account
    - Select the Robot image
    - Select **Create Robot Account**
    - That username/password will be added into the `QUAY` variables.
    - Add **Write** permissions to the repository by the robot account