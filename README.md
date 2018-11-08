# ReactTutorial

JSFiddle with JSX: http://jsfiddle.net/reactjs/69z2wepo/
JSFiddle without JSX: http://jsfiddle.net/reactjs/5vjqabv3/

https://www.facebook.com/videocall/incall/?peer_id=671736480

https://facebook.github.io/react/downloads.html


Tools
There are several tools that can help make React development even more fun. To access the 
JSX transformer that can be installed for the command-line via  npm, use this command:
npm install -g react-tools
There are several utilities and editor integrations, most of which are listed at 
https://github.com/facebook/react/wiki/Complementary-Tools#jsx-integrations.

  https://facebook.github.io/react/docs/
addons.html

one example of a useful 
addition is a project called react-router , which provides routing for React applications.

Intro to React
Page -34
CHAPTER 3




https://jsx.github.io/
https://facebook.github.io/react/docs/hello-world.html
https://facebook.github.io/react/docs/installation.html
1=> To install React with npm, run:
npm init
npm install --save react react-dom


2=>babel installation =>  Babel setup instructions explain how to configure Babel in many different build environments.

https://babeljs.io/docs/setup/#installation

npm install --save-dev babelify

Create .babelrc configuration file
npm install babel-preset-env --save-dev

In order to enable the preset you have to define it in your .babelrc file, like this:
Copy
{
  "presets": ["env"]
}

Note: Running a Babel 6.x project using npm 2.x can cause performance problems because of the way npm 2.x installs dependencies. This problem can be eliminated by either switching to npm 3.x or running npm 2.x with the dedupe flag. To check what version of npm you have run


Copy
npm --version


creating react app
npm install -g create-react-app
create-react-app my-app

cd my-app
npm start

3=>	
Make sure you install babel-preset-react and babel-preset-es2015 and enable them in your .babelrc configuration, and you're good to go.

//babel-preset-react 
npm install --save-dev babel-cli babel-preset-react
create .babelrc and paste code below
{
  "presets": ["react"]
}


//babel-preset-es2015
npm install --save-dev babel-cli babel-preset-es2015
// .babelrc file paste
{
  "presets": ["es2015"]
}

//.babelrc configuration
http://babeljs.io/docs/usage/babelrc/
