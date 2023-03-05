# test-deploy-vite-pages-using-actions

![Deploy Status](https://github.com/thomaslaurenson/test-deploy-vite-pages-using-actions/actions/workflows/deploy.yml/badge.svg)

A repo to test building and deploying a Vite + ReactJS project using GitHub Actions.

To copy the workflow, you need to configure GitHub pages using Actions for deployment first. To do this, in the target repo:

- Navigate to `Settings`
- Select `Pages`
- Under the `Build and deployment` section
- Set the `Source` section
- Set this to `GitHub Actions`

Then add the workflow as it appears in this repo in the `.github/workflows/deploy.yml` file.
