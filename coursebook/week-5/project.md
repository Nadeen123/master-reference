# Project

Create a web app that includes some form of user input and provides users with content from an API that is regularly updated - e.g. the same user input submitted at different times could result in different content being retrieved. 💁‍

A good example could be a news app but feel free to be creative!

The key difference between this project and your API week project is that you will be making your **API calls from the back-end** and **testing your server**.


### Example:

#### User Stories:
'As a student at F&C I want to know all the train departure times from Finsbury Park tube station, so that I can get home in time for dinner'.🚉🍛

'As a regular commuter, I want to input which direction of travel I am interested in so that I can see information that is relevant to me.'

This news feed could be created with data provided via the [TFL API](https://api.tfl.gov.uk/).

You can build on this user story or create your own user stories as long as they are consistent and the below specs are fulfilled.

### Goals:
1) Use at least 1 API 

2) Make your API calls from the back-end using the Request module (or one you build yourself)

3) Your server should contain a minimum of 2 routes

4) We expect to see lots of tests! Modularise your code and test all your pure functions. Write tests for as much of your back-end and front-end logic as you can. We don't expect tests on the DOM.

5) Test your server routes.

6) Host your project on Heroku, see [resources](https://github.com/foundersandcoders/master-reference/blob/master/coursebook/week-5/resources.md)

7) Use module.exports and require to break a single large server file into smaller modules.

8) Consider a good server file structure based on what we have discussed over the week.

9) Employ continuous integration on your project with Travis or a similar tool. (If you decide to use Travis, we strongly recommend that you host this project in your own repo rather than in your cohort's FAC repository to avoid all builds getting queued together)

10) Use CodeCov or a similar tool to report and track test coverage.

11) Include Error Handling. For example:
  - if a user attempts to make a request to a non-existent route to your server (404 - as mentioned above), provide the user with a custom response.    
  - if there is a [programmer error](https://github.com/foundersandcoders/error-handling-workshop#kinds-of-errors) on your server (e.g. a handler function does not act as intended), provide the user with a custom response (500 status code).


12) Display continuous integration and code coverage badges on your project README. 

### Stretch goal 😊:

14) Research and use Nock to mock the response of external API calls in your tests, and write tests for server routes that make API calls.

15) Create a route and functionality for a POST request.
