# Basic Framework For Front End Vanilla.js Projects

## Preflight Check
1. Make sure you are in the project file
1. pwd current working directory
1. One you are sure you are in the right location, run npm install from framework folder.
1. Run npm install from the framework root folder. This will create the node_modules and install the dependancies found in the package.json file.
```bash
  npm install
```

1. Run development build using the parcel bundler.
```bash
   npx parcel src/index.html
```
or
```
  npm start
```

1. Run production build using the parcel bundler.
```bash
   npx parcel build src/index.html
```
or
```
  npm run build
```

# GIT SETUP
1. .gitignore ignores files and they will not be uploaded to remote repository.

1. Set up repo from VS Code
1. User Profile Icon
1. Sign in to sync settings
1. Sign in with github
1. Click on the green button to accept
1. Click on the Source Control tab
1. Publish to Git, select public repo
1. Publish the folder to the github repo

# Remove Repo
1. Go to the Github repo
1. Select settings
1. Scroll to the bottom
1. Delete the repo

## If You Make an Init Mistake
Search Your Local Repository for Hidden Files
```bash
  ls -lah
```

Looking for a File That Says
```
  rm -rf .git
```

Then re-init your repository

# Deploying to Netlify
1. Account at netlify and log in
1. Click on team name sleect sites tab
1. Site -> click on the deploy from git
1. Show your repo's
1. Select the repo to build
1. Make sure to write the correct build command
```
parcel build src/index.html
```
1. Netlify will deploy the repo

# VS Code
1. Make changes
1. Commit the changes
1. Push the changes to remote repo
1. Netlify sees changes and builds a new site
