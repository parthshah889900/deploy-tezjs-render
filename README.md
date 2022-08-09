# Deploy to Render
In this guide, you will learn how to deploy your TezJs Site to  Render.

## Deployed Url:
https://tezjs-deploy-render.onrender.com/

## Preparing for deployment:
Run the following command to create tezjs project:
  - `npm create tez@latest`
  - `cd [projectName]`
  - `npm install` - for installing the required dependencies
  - `npm run build` - for build the project
  - `npm run dev` - for run the project

## Pre-requisites:
  - Need to authrize with render account.
  - To deploy your Tezjs project, make sure it has been pushed to a Git repository.

## Deploying your Tezjs project to Render:
  Go to render dashboard for creating project:  https://render.com/
1. Create a new project in Render.
2. Connect your repositoty code with render app.
3. Give the build command - `npm run build`
4. Give the build folder name - `dist`
5. Click on the button - `Deploy Now`

## References:
- [Renders Docs](https://render.com/docs/)
- [Render Deployments](https://render.com/docs/deploy-vue-js)
