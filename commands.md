npm init -y

# set default values
npm set init-author-name 'Jens Hoffmann'

# delete author name
npm config delete init-author-name


// npm install --save
npm install -S

// npm install --save-dev
npm install -D

npm i karma  

// onnly wanna see dependencies that are one level deep
npm list --depth 1

// will list all global dependencies
npm list --global true
npm list --global true --depth 0

npm list --global true --depth 0 --long true

npm list --global true --depth 0 --json true

npm list --global true --depth 0 --parseable true

npm list --depth 0 --prod true

npm ls

npm uninstall underscore

# uninstall global package
npm  r underscore -g 

npm i underscore@">=1.1.0 < 1.4.0"

# install specific version 
npm i underscore@1.8.1

# install the latest version of the major release
"underscore": "^1.5.1"

// update production dependencies
npm update --prod

npm update underscore

# update all the global packages
npm update -g


// go to the registry
registry.npmjs.org/underscore

// go directly to the page
npm.im/underscore

npm search underscore

// npm compares the installed packages with the package.json file
npm prune 

// will remove all the dev dependencies
npm prune --production

// go to the repo of underscore
npm repo underscore

# update npm with admin privileges
npm i npm@latest -g

# run a custom script

npm run uglify

package.json

"scripts": {
    "uglify": "gulp uglify"
}

gulpfile.js
gulp.task('uglify', function() {
})

// add an npm user
npm adduser

git remote add origin 'url'
git push --set-upstream origin master
git push origin master

# publish the npm project
> npm publish






















