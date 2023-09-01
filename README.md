# A Look at Go
Kevin Harris

This site introduces how to play the board game Go.

## Template solutions
1. "server.js" line 9: absolute path instead of relative `'public'`
2. "about.html" line 27: missing `"` in title attribute.
3. "site.js" line 5: Missing `()` to call `event.preventDefault`

## Node scripts
1. `npm start` starts the server.
2. `npm test` runs our linters.

## New configuration this week
1. Initialize a node project with `npm init --yes`. This creates
  a Node project using default answers.
2. Initialize StyleLint with `npm init stylelint`.
3. Install our JS and HTML linters with `npm install
  --save-dev standard html-validate`. We now have our linters 
  for JS, CSS, and HTML installed. Development dependencies
  are only installed by npm in development environments.
  In production environments, these are ignored.
  See the "devDependencies" key in "package.json" to verify
  the installation.
4. Install Express, a lightweight web server framework, with
  `npm install express`. You should see Express listed in
  the "dependencies" key in "package.json".
5. Added `"type": "module",` to "package.json".
6. Changed `"test"` in "package.json".  
7. Created a "public/" directory for static assets.

## Development
1. Created "server.js" to run the site.
2. Created static assets.

