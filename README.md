# Club Manager

#### Authored by Dylan Stackhouse, 4/7/17

## Description
A website for the management of a particular club, a magic guild. The site will catalogue all members along with their roles in the guild along with other relevant information about them. The site also allows for administrators to add, edit, and delete members of the guild roster.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Angular](https://angular.io/)
* [Angular-CLI](https://cli.angular.io/)

## Setup

* $`git clone https://github.com/DylanCStack/Meal-Tracker.git`
* $`cd Meal-Tracker`
* $`npm install`
* $`bower install`
* $`ng serve`
* Navigate to localhost:4200 in a web browser


## Entity creation plan/workflow
  1. $ `ng g c about`
  2. $ `ng g c contact`
  3. $ `touch app.routing`
  4. $ `ng g c roster`
  5. Create firebase project and database
  6. $ `touch seed.json`
  7. $ `touch api-keys.ts`
  8. $ `ng g s MemberService`
  9. $ `ng g c profile`
  10. $ `ng g p RoleFilter`
  11. $ `ng g c admin`


##### Angular CLI
This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.26.

To get more help on the `angular-cli` use `ng help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).