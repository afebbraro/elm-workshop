Back to [Main Page](../README.md)

# Introduction to Elm (Setup)

Before the workshop, you'll want to make sure that your environment and project are setup. Follow the steps below to accomplish this. 

#### Environment
 
1. Install <a href="https://nodejs.org" target="_blank">Node.js 6.9.2</a> or higher

2. Install the Elm Runtime `npm install -g elm`

3. Install elm-format by running `npm install -g elm-format`

4. Install elm-live by running `npm install -g elm-live@2.6.1`

Note to Mac OS X users: If step 4 gives you an EACCESS error, try this fix:

`sudo chown -R $(whoami) $(npm config get prefix)/{lib/node_modules,bin,share}`

Then re-run steps 3 and 4

Note: Tab characters are syntax errors in Elm code, so make sure your editor is set to use spaces for this workshop!

#### Setting up the Project
On your computer, complete the following steps:
1. Navigate to a directory on your computer where you have permission to create and edit directories and files
2. Run `git clone https://github.com/Elm-Detroit/elm-workshop.git`
3. Run `cd elm-workshop/setup`

#### Verify Your Setup
1. Run `npm start` and a browser should open. You should see the following page if everything went as planned:

    <img src="https://github.com/Elm-Detroit/elm-workshop/blob/master/static/images/verification-success.png" width="350" alt="Verification Image" />

If all went well, click on the link below to go to Part 1

Go to [Part 1](../part1/README.md)