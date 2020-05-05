# Povigo website
[![Netlify Status](https://api.netlify.com/api/v1/badges/44b6dc71-87ad-4320-b999-09eac1441d3d/deploy-status)](https://app.netlify.com/sites/povigo/deploys)
Based on [bootstrapmade appland template](https://bootstrapmade.com/free-bootstrap-app-landing-page-template/)

# Development
1. Run `npm install`
2. Run `npm start`
3. Watch changes on `http://localhost:3000`
4. Develop

# Build
1. Run `npm install`
2. Run `npm run dist`
3. Website available in `dist` folder

# Deploy
1. Make your changes on the `develop` branch, `commit` and `push` them
2. Netlify will automatically [build and deploy](https://app.netlify.com/sites/povigo/deploys) the develop branch
3. Validate the deployment of the `develop` branch [here](https://develop--povigo.netlify.app/)
4. If everything looks good create a pull request from `develop` to `master` on GitHub
5. Wait for the netlify status checks to succeed
6. Netlify will automatically [build and deploy](https://app.netlify.com/sites/povigo/deploys) a deploy preview
7. Validate the deployment of the `pull request`
8. Merge the pull request into `master` branch
9. Netlify will automatically [build and deploy](https://app.netlify.com/sites/povigo/deploys) to production
10. Validate the deployment to `production` [here](https://www.povigo.be) 