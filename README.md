# Steps to deploy application using ghpages

Deployed application: [https://nateusse.github.io/angular-ghpages/](https://nateusse.github.io/angular-ghpages/)

## Steps
1. Install package ng add angular-cli-ghpages
2. Commit and push files. The gh-pages will be created automatically.
3. Build project with  ng build --base-href "https//nateusse.github.io/angular-ghpages/
4. Indicate route to deploy with npx angular-cli-ghpages --dir=dist/angular-ghpages/. If files where created in dist/browser/, take them out 
