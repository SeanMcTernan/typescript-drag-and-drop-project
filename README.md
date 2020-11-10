# TS Drag & Drop Project <a href="https://github.com/SeanMcTernan" target="_blank"><img src="https://raw.githubusercontent.com/SeanMcTernan/SeanMcTernan/7c1dcc08830e2087866a9d06c1f37d7b431edf82/ReadMe_Images/ReadMe_Badge_Small.svg" alt="Site badgeBy Sean Mc Ternan" width="120"/></a>


<img src="https://raw.githubusercontent.com/SeanMcTernan/SeanMcTernan/dd6d823a734467b1ad4f5bc90a496b6642222ca3/ReadMe_Images/TypeScript-Drag-And-Drop/TS_Drag%26Drop_Logo.svg" align="right"
     alt="TS Drag & Drop Project App Image By Sean Mc Ternan" width="120" height="178">


A small Typescript project, to explore drag and drop functionality within a browser. 


## Technologies Used
| Name                                                        | Purpose                                                                                                    |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [NodeJS](https://nodejs.org/en/)         | Main programming language for the project |
| [TypeScript](https://www.typescriptlang.org/)         | Main programming language during development|
| [WebPack](https://www.npmjs.com/package/webpack)      | To bundle the package |
| [Lite-Server](https://www.npmjs.com/package/lite-server) | To run the application on a local server |
| [TS-Loader](https://www.npmjs.com/package/ts-loader) | To help load TypeScript for Webpack          |

### The App

<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/TypeScript-Drag-And-Drop/TS_Drag&Drop_Cap_1.png?raw=true" alt="Drag & Drop Image" width="738">
</p>

The project consists of a basic form field, whereby a user can add a Title, Description and the number of people assigned to a project. There is a small amount of error checking associated with the form so that users cannot input incorrect information. 
Once Add Project is selected the project is automatically added to Active Projects. The user can then click and drag the project to finished projects. You may also move a project back to active from finished projects. You can see the project in action here:

<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/TypeScript-Drag-And-Drop/Drag&Drop.gif?raw=true" alt="Drag & Drop Gif" width="738">
</p>


### Motivation & what was learned

In May 2020 I started working with [RURU-Software](https://github.com/ruru-software) on their delivery app. The app was built using Typescript. Even though I had completed [Understanding-Typescript](https://www.udemy.com/course/understanding-typescript/) by Maximilian Schwarzmüller in early 2019, I had never gotten an opportunity to apply my knowledge in a real-world application. When the opportunity had come up to work with RuRu, I checked back on Max's course and was happy to see an updated version was available for 2020, this was one of the many projects I had gotten to work on this course, while at the same time working for RuRu.

I learned a great deal about browser tools and type safety while working on this project. I had seen applications like [Trello](http://www.trello.com) use the drag and drop feature to great effect, so I was happy to learn what was required while working on this project.

### Install Instructions

1. Clone/Download the Repository 
2. From the folder run `npm install`
3. Run `npm start`
4. Vist http://localhost:8080/ and play with the project

### Development Time: 2 days
