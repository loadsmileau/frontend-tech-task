__Language :__ English | [Bahasa Indonesia](README_ID.md)

# Frontend Technical Task
Web App for Lunch Recipes Suggestion

## Time Management
There is no deadline to do this tech task. It's up to you how you manage your time to accomplish at least the requirements.

## Assessment

Our assessment criteria will pay attention on:
- How the application is structured.
- Code quality (Clean code).
- Quality of tests.
- Interpretation of the problem.
- Use of `git`.
- Implementation and final execution.
- Commits, as this will allow us to understand some of the decisions you make throughout the process.

## User Story
As a User I would like to get a set of recipes what I can have for lunch today based on the contents of my fridge, so that I quickly decide what I’ll be having.

__Acceptance Criteria__
- Given that I have started the app, I should input my preference lunch date or it would be today date if it is empty
- Given that I have made a request to the `/ingredients` endpoint, I should receive a JSON response of the ingredients in my fridge.
- Given that I get the options of my ingredients, I should choose some ingredients to get the recipes.
- Given that an ingredient is past its `use-by` date (inclusive), I should not be able to choose that ingredient.
- Given that I have choosen some ingredients, I should request to the `/recipes` endpoint with `?ingredients=<title-1>,<title-2>,<title-n>` as a query parameter.
- Given that I get the result of the available recipes, I should see list of the recipes as well the ingredients to make per recipes.

__Additional Criteria__
- The application SHOULD contains unit / integration tests (e.g. using `Mocha.js`).
- Any dependencies MUST be installed using dependency management tools (`npm` or `yarn`).
- Any installation, build steps, testing and usage instructions MUST be provided in a `README.md`
file in the root of the application. __Do not use a autogenerated file__

## Framework
Use the `React.js` or `Vue.js`.  

## API Endpoint
__Documentation__

https://documenter.getpostman.com/view/9359572/SW17TFmK

__Mock Base URL__

https://lb7u7svcm5.execute-api.ap-southeast-1.amazonaws.com/dev

__Instruction__
1. Use `/ingredients` to get all of my ingredients on my fridge
2. Use `/recipes?ingredients=<title-1>,<title-n>` to get recipes based on the preferred ingredients title
 
## Submission
The application should be committed to a `public` repository on `GitHub` or `BitBucket` (`<lastname>-<firstname>-techtask-frontend`) and simply send us a link to the repository.
