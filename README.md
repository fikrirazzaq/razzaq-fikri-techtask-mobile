__Language :__ English | [Bahasa Indonesia](README_ID.md)

# Mobile Technical Task
Apps for Lunch Recipes Suggestion

## Time Management
There is no deadline to do this tech task. It's up to you how you manage your time to accomplish at least the requirements.

## Assessment

Our assessment criteria will pay attention to:
- How the application is structured, and files are organised.
- Code quality (Clean code).
- The quality of test cases in your test suite.
- Interpretation of the problem.
- Use of `git`.
- Implementation and final execution.
- Commits, as this will allow us to understand some of the decisions you make throughout the process.

## User Story
As a User, I would like to get a set of recipes what I can have for lunch today based on the contents of my fridge so that I can quickly decide what I'll be having.

__Acceptance Criteria__
- Given that I have started the app, I should input my preference lunch date, or it would be today date if it is empty
- Given that I have made a request to the `/ingredients` endpoint, I should receive a `JSON` response of the ingredients in my fridge.
- Given that I get the options of my ingredients, I should choose some ingredients to get the recipes.
- Given that an ingredient is past its `use-by` date (inclusive), I should not be able to choose that ingredient.
- Given that I have chosen some ingredients, I should request to the `/recipes` endpoint with
 `?ingredients=<title-1>,<title-2>,<title-n>` as a query parameter.
- Given that I get the result of the available recipes, I should see a list of the recipes as well as the ingredients to make per recipes.

__Additional Criteria__
- Fork this Flutter project as a base for your project.
- The application MUST have more than one screen and navigation.
- The application MUST contain unit / widget tests (e.g. using the `flutter_test` package).
- The application MUST be completed using an `OOP` approach.
- Any dependencies MUST be installed using dependency management tools (`Pub` for Flutter).
- Any installation, build steps, testing and usage instructions MUST be provided in a `README.md`
file in the root of the application. __Do not use a autogenerated file__

## Framework
Use the [__Flutter__](https://flutter.dev/docs/get-started/codelab) framework.  

## API Endpoint
__Documentation__

https://documenter.getpostman.com/view/9359572/SW17TFmK

__Mock Base URL__

https://a61d556b-57ca-423f-8706-2e8dec75d714.mock.pstmn.io

__Instruction__
1. Use `/ingredients` to get all of my ingredients on my fridge
2. Use `/recipes?ingredients=<title-1>,<title-n>` to get recipes based on the preferred ingredients title

__NOTES : This API is only a mock server to simulate the request and response body. So the result of the API does not affect your final result.__ 
 
## Submission
The application should be committed to a `public` repository on `GitHub` or `BitBucket` (`<lastname>-<firstname>-techtask-mobile`) and simply send us a link to the repository.

## Getting Started with Flutter

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view [online documentation](https://flutter.dev/docs), which offers tutorials, samples, guidance on mobile development, and a full API reference.
