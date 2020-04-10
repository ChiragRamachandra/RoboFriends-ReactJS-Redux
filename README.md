# robofriends
Tutorial for udemy course - React
To run the project:

1. Clone this repo
2. Run `npm install`
3. Run `npm start`# RoboFriends-ReactJS-Redux



To Deploy the package to Git hub Pages:

In the package.json file add "homepage": "https://myusername.github.io/my-app",
npm install --save gh-pages
Add these 2 in scripts "scripts": { "predeploy": "npm run build", "deploy": "gh-pages -d build" }
npm run deploy
Incase you run into errors for npm run deploy. Use via the GitHub Terminal.

Also try: rm -rf node_modules/gh-pages/.cache

so that the cache is cleared.