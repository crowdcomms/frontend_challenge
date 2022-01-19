# Frontend Coding Challenge

## Introduction

You have been tasked with creating a new feature for our events app using the latest version of Angular.  The feature will let users view speakers in the app.

You can use any other frameworks/libraries you like to help with styling, eg material, ionic. The app should be architectured (specifically the folder structrure) in way that will scale to a large enterpise sized app.

***Note: This is purely for testing purposes and the feature will not be used by us in any form.***

## Getting Started

1. Create a new GitHub repo and commit the basic app scaffolding
2. Fetch the speakers from the api using the endpoint "https://randomuser.me/api/?results=20&page=1'"
3. Display the speakers in a list (only show the details you deem suitable)

## Requirements

- Show a list of a speakers for the event.
- Allow the user to filter the list via a searchbar, this should be performant. 
- Follow the best practices of Angular development and be well documented.
- The speakers page should sit under the route of `/speakers`
- Be presentable & optimised for performance.
- Unit tests (jest / jasmine) for the main page component if you can.

## Nice To Haves
All of these features are entirely optional. If you find that you have extra time or just want to do more then feel free to pick some ideas from below.

- Paginate the list of speakers.
- Create a detail page for a speaker which shows additional information about them.
- Implement a state management system, eg NgRx.
   
## Time Limit

Take as long as you want on this project. But we expect the core requirements to take no longer than a few hours.

## Other

You should *commit regularly* and follow the [Angular guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines) for commit messages.  Example commit message: "fix(people list): people not showing"

Feel free to use the README.md of your project to explain any decisions or talk about your work.