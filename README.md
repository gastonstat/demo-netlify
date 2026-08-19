# README

Demo website to test deploying to Netlify.

<https://netlificacion.netlify.app/>


## Deploying website to Netlify from GitHub

To deploy a website to Netlify from GitHub, you need to link your GitHub repository to your Netlify account so that Netlify can automatically build and publish your site every time you push code changes.

### 1. Connect GitHub to Netlify

- Log into the Netlify Dashboard.
- Click Add new project.
- Select Import an existing project.
- Choose GitHub as your Git provider.
- Authorize Netlify to access your GitHub account.

### 2. Choose Your Repository

- Select your target GitHub organization or user account.
- Choose the specific repository you want to deploy.

### 3. Configure Build Settings

Netlify will attempt to auto-detect your framework (like React, Vue, Next.js, or Hugo). Verify the following settings:

- Branch to deploy: Usually `main`
