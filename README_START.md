# HOW TO START NEW PROJECT WITH GULP
# INSTRUCTION


# Step 0.

// If you've previously installed gulp globally, run:

npm rm --global gulp


# Step 1.

// Check for node, npm, and npx. Run in terminal:

node --version

npm --version

npx --version

// (If they are not installed follow the instructions here: https://nodejs.org/en/)


# Step 2.

// Install the gulp command line utility:

npm install --global gulp-cli


# Step 3.

// Create a project directory and navigate into it:
// (not necessary, simply can do it from file manager)

npx mkdirp my-project
cd my-project


#Step 4.

// Create a package.json file in your project directory:
// (This will guide you through giving your project a name, version, description, etc.)

npm init


#Step 5.
// Install the gulp package in your devDependencies:

npm install --save-dev gulp

// Verify your gulp versions:

gulp --version

// (Ensure the output matches the strings below or you might need to restart the steps in this guide.)

CLI version 2.0.1
Local version 4.0.0


#Step 6.

// Create a gulpfile (or use the template in this directory)



#Step 7.

// Check and update folders structure & gulpfile. Test it:

gulp

(the gulp task in template gulpfile will run 'gulp build' and 'gulp dev' and show your project live)


#USEFUL LINKS:


Gulp.js Quick Start manual:
https://gulpjs.com/docs/en/getting-started/quick-start

Gulp for babies-beginners (video):
https://www.youtube.com/watch?v=vW51JUVT66w&list=PL2WcN5hFpzVTWt51dFhEovQkzk5DENUOa&index=42&t=0s

Gulp for babies-beginners (text):
https://webdesign-master.ru/blog/tools/2016-03-09-gulp-beginners.html

Setting NPM and Gulp. SASS compilation - (video) from Dmitriy Lavrik:
https://www.youtube.com/watch?v=EtbZQ6qWuJ4&list=PL2WcN5hFpzVTWt51dFhEovQkzk5DENUOa&index=43&t=0s

Gulp 4 webinar - (video) from Dmitriy Lavrik:
https://www.youtube.com/watch?v=9qbdCruqpys&list=PL2WcN5hFpzVTWt51dFhEovQkzk5DENUOa&index=44&t=0s

Webpack 4 webinar - (video) from Dmitriy Lavrik:
https://www.youtube.com/watch?v=MRlBKfGktwI&list=PL2WcN5hFpzVTWt51dFhEovQkzk5DENUOa&index=47&t=0s

Gulp+Webpack webinar - (video) from Dmitriy Lavrik:
https://www.youtube.com/watch?v=c773_a4eEtk&list=PL2WcN5hFpzVTWt51dFhEovQkzk5DENUOa&index=46&t=0s

