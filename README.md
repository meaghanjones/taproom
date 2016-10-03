# _Taproom_

#### _This application was a in class exercise to build a one page app using Angular2, August 2016_

#### By _Meaghan Jones and Olivia Hinton_

## Description
For this project we built a small Angular app for a bar to keep track of their kegs.

Here are the user stories we used to build the app. As a bartender ...

1. I want to fill out a form when I tap a new keg to create a display for it.
2. I want to see what kegs I have available. For each keg, I need to see its name, brand, price and alcohol content.
3. I want to see a display of how many pints are left in a keg. A full keg has 124 pints in it.. I want to be able to click a button on a display of a keg whenever I sell a pint of that kind of beer and have the display of how many pints are left decrease by 1.
4. I want to be able to see all the kegs that have less than 10 pints left so that I can be ready to change them.
5. I want to be able to edit a keg's properties after entering them.
6. I want to have kegs color coded to show me at a glance if they are cheap or expensive - say greater or less than $5 per pint. I also want to use the alcohol content property to display stronger beers differently than weaker beers.

## Setup/Installation Requirements

## Setup 

Steps when beginning a new project, or cloning an existing one:
1. Run npm install and bower install to install dependencies.
2. Install any global packages such as gulp, bower, sass, typescript, and our text editor's typescript packages.
3. Build the project with gulp build.
4. Run it with: gulp serve.

1. user npm to install bower globally. user bower to manage front-end dependencies for the app
2. run bower's `init` command to create the manifest file
```
$ npm install bower -g
$ bower init
```
any time we need a front-end dependency we can add it using

```
$ bower install packagename --save
```

## Known Bugs

_This is a class project and may have some bugs._

## Support and contact details

_Please email me at meaghan.m.jones@gmail.com if you have any questions about the code._

## Technologies Used

_Angular 2_

### License

_This software is licensed under the MIT license._<br>
Copyright (c) 2016 **Meaghan Jones**
