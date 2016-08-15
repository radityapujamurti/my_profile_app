# My Profile App

This sample application is skeleton for a typical [AngularJS Material](http://angularjs.org/) web app: comprised of a Side navigation area and a content area. You can use it to quickly bootstrap your angular webapp projects and dev environment for these projects.

> The start app doesn't do much... it just demonstrates how to override a theme and how to use the side navigation component. Try shrinking the window size and watch the sideNav auto-hide. You can temporarily show the sideNav by clicking on the upper left menu button.

## Getting Started

To get you started you can simply install live-server and run a standalone development server locally with Internet.

### Prerequisites

You need the Internet to run the necessary dependencies from the CDN.

You will also need NODEJS to install a test development server.
Highly recommended: live-server

```
npm install -g live-server
```

## Directory Layout

```
app/                    --> all of the source files for the application
  app.css               --> default stylesheet
  src/                  --> all app specific modules
     avatars/           --> package for avatar features
      avatarService.js  --> angular service used to simulate remote dataservices for avatars.
  app.js                --> main application module
  index.html            --> app layout file (the main html template file of the app)
```

## Running the app

Right after you installed the **live-server** package, you may run the following command:

```
cd app; live-server
```

Your browser will auto load the app and you should see the starter app running.

## Task requirements
- Explore and figure out [AngularJS](http://angularjs.org/) as well as [Angular Material](http://material.angularjs.org/).
- This boilerplate is inherited from the [Material Starter](https://github.com/angular/material-start)
- Understand how RESTful APIs work, in essence, the **C** reate, **R** ead, **U** pdate, **D** elete workings.
- Remove the statically embedded data service and instead make use of the provided *http* or *$resource* services or any package you would like to make use of, to call the Profile API.
- Read and understand from the open source API, [Random User Generator](https://randomuser.me/)
- Integrate that with this profile app
- Provide a route where you can add new Profile
- Provide a route where you can edit a Profile
- Provide a route where you can delete a Profile
- Provide a route where you can filter options of Profile Listing such as ladies only
