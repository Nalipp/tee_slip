## commit 1
initial commit
```
README.MD
.gitignore
.gitinit
.npm init
buildScripts/server.js
src/index.html
```

```
"npm-run-all": "3.1.1" -> allows you to start mulitple requests in parallel
"nsp": "2.6.2"         -> scans packages for vulnerabilities
```

## commit 2
install babel to transplie es6 to es5

```
// files changed
update package.json
```

## commit 3
install webpack and eslint

minifiy and bundle code files with webpack and install eslint linter

```
// files changed
update package.json
update server.js
update src/index.html

create webpack.config.dev.js
create src/index.js
create src/index.css
create .eslintrc.json
```
## commit 4
set up travis

https://travis-ci.org/

\+ new repository

select and turn on repo from the list

```
// files changed
.travis.yml
```

## commit 5
set up test configuration

```
// files changed
update package.json

create buildScripts/testSetup.js
create src/index.test.js
```

## commit 6
connect to the database

create user file structure

```
// files changed
update server.js

create config.js
create mongoose.js
create users file structure
```

## commit 6
deploy to heroku

```
// files changed
update server.js

```
