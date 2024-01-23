# ISNCSCI

There are four GitHub projects relevant to the most recent work on [ISNCSCI](https://github.com/praxis-isncsci)

- [algorithm](https://github.com/praxis-isncsci/algorithm) 
- [ui](https://github.com/praxis-isncsci/ui)
- [ionic-app](https://github.com/praxis-isncsci/ionic-app)
- [public-site](https://github.com/praxis-isncsci/public-site)

## praxis-isncsci/algorithm 

The algorithm project contains the ISNCSCI Algorithm code which is used in the calculations and classification on spinal coord injuries. This is a library meant for developers to use in their own projects and interfaces to automate the classification of ISNCSCI exams. The library is published as an [NPM package](https://www.npmjs.com/package/isncsci?activeTab=readme). 

## praxis-isncsci/ui 

This project contains a collection of web components, icons, and styles that can be used to build interfaces to classify ISNCSCI exams. A component in this library is a web application that serves as an example on how the components can be used to build a fully responsive app. 
The requirements for this project come from [Figma](https://www.figma.com/file/82mMuohRV0zPWnZbZ5upup/isncsci-app?type=design&node-id=207-9677&mode=design&t=bsPp0V9VaKYOoAti-0). This Figma file contains the design tokens used in the project 
This project has GitHub actions that automatically publish the code to the following places: 

- [Chromatic](https://www.chromatic.com/builds?appId=64f8d7c6e093108e99084a70) - Used for visual testing of the components. This service has a library of screen captures used to compare visual changes on every commit.
- [Storybook](https://64f8d7c6e093108e99084a70-lqlepbrspv.chromatic.com/?path=/docs/app-app--docs): Has the library of components contained in this project. This instance of Storybook is built by Chromatic and shows the code on the main branch. 
- [NPM package](https://www.npmjs.com/package/isncsci-ui): The UI library is published to NPM so that developers can add it to their own projects.
