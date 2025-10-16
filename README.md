# HNG13 Stage 0 DevOps Project

Use this template to capture the key details required for the task.

## Project Details

- **Name:** `<Your Name>`
- **Slack Username:** `@<your-slack-handle>`
- **Project Description:** `Forking the challenge repo, customizing the provided landing page, and deploying it to a Google Cloud VM running NGINX on port 80 via an automated GitHub Actions workflow.`
- **Server IP/Domain:** `<Add this once the application is deployed.>`

## Deployment Notes

- The workflow uses GitHub Secrets for credentials (`GCP_HOST`, `GCP_USERNAME`, `GCP_SSH_KEY`, and any other environment-specific values).
- Deployment is executed through an Appleboy SSH action defined in `.github/workflows/deploy.yml`.
