# Example Package

**example-package** is a simple Python package published to Cloudsmith using GitHub Actions.

## Workflows

### 1. Build Workflow
This workflow is responsible for building the Python package. It ensures that the package is correctly packaged and ready for distribution.

### 2. Staging Push Workflow
Once the package is built, this workflow pushes it to the Cloudsmith staging repository. This allows for testing and verification before production.

### 3. Promotion Workflow
When a package is tagged as "ready for production," this workflow promotes it from the staging repository to the production repository on Cloudsmith.

## Getting Started

1. **Build the Package**: Trigger the build workflow by pushing changes to the main branch.
2. **Push to Staging**: Once the build is successful, the staging push workflow will automatically run.
3. **Promote to Production**: Tag the package as "ready for production" to trigger the promotion workflow.
