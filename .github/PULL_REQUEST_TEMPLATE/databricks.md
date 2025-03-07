# Databricks Pull Request Template

## What type of asset is this? (Check all that apply)

- [ ] Notebook
- [ ] Job
- [ ] Library
- [ ] Model
- [ ] Workflow
- [ ] Dashboard
- [ ] Cluster Configuration
- [ ] Other: _please describe here_

## Description of Changes

<!---
Provide a clear and concise description of the asset(s) you are adding or updating.
- What changes were made?
- Why are these changes necessary?
- Include details about improvements, bug fixes, new features, or optimizations.
If this is linked to an existing issue, mention it here (e.g., "Fixes #123").
-->

## Affected Components

<!---
List all Databricks components affected by this PR (e.g., clusters, jobs, models, etc.).
If applicable, describe the downstream impact and any changes required for existing workflows.
-->

- [ ] Clusters
- [ ] Jobs
- [ ] Notebooks
- [ ] Libraries
- [ ] Models
- [ ] Repos
- [ ] Other: _please describe here_

## Deployment Instructions

<!---
Provide detailed instructions for deploying this bundle in Databricks. Include:
- Steps for applying the changes (e.g., deploying notebooks, jobs, etc.)
- Any cluster configurations or environment changes required
- Any additional setup, like secrets or database credentials, needed for deployment
-->

## Testing and Validation

<!---
Describe the testing performed for this bundle:
- How did you verify the assets function as expected?
- Any unit or integration tests included?
- Any environment-specific tests (e.g., tested in staging or production)?
Be specific and link any test results if applicable.
-->

- [ ] Unit tests have been included
- [ ] Integration tests have been included
- [ ] Manual validation was performed in the following environments:
  - [ ] Development
  - [ ] Staging
  - [ ] Production

## Checklist

<!---
Ensure the following items have been completed. If not applicable, remove them.
-->

- [ ] My asset bundle follows Databricks best practices.
- [ ] I have thoroughly tested the assets.
- [ ] I have documented any new configurations, environment variables, or secrets.
- [ ] I have updated the README or relevant documentation (if applicable).
- [ ] I have included necessary assets like libraries or configuration files.

## Dependencies and Compatibility

<!---
List any dependencies this bundle has (e.g., libraries, runtime versions, external APIs, etc.).
If any backward-incompatible changes were introduced, explain here.
-->

- [ ] Runtime version compatibility: _please specify version(s)_
- [ ] External dependencies: _please list here_

## Migration Steps (if applicable)

<!---
If this PR introduces changes that require migration steps (e.g., upgrading models or libraries), list the steps here.
Include information about data migrations, config changes, or cleanup tasks.
-->

## Additional Notes

<!---
Add any additional information that reviewers should be aware of.
This could include specific deployment concerns, potential impact on existing workflows, or any limitations.
-->
