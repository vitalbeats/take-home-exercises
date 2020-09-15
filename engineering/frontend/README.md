# Frontend mobile developer
As part of the interview process you will have been asked to work on an exercise.

## Excercise
At vitalbeats we have a mobile app build with react-native targeted to patients which allows them to track their personal info, answer questionnaires, contact clinicians and contact support from us.

The excercise consists in implementing a `Bookshelf` application that should run consistenly in iOS and android. You don't need to use axios to connect to any `api`, just mock the response in the `side-effects` layer (redux-saga) with the mock data provided inside the `./data` directory.

The application must include a navigation from the bookshelf to the selected book and a navigation sidebar in the `bookshelf view` to select _filter_ books by genre.

Once it's done invite sent us the url to the repo where you've implemented the solution. (If your repo is private let us know so we can send you a username to share).

You can use any boilerplate to get you started, except for **expo**.

Please refer to the `mockup` wireframe to understand the expected design, located in `./mockup` (if you have sketchyou can open the file, otherwise the png file has everything you need). It's a low level design so you can decide colors, fontsizes, but keep in mind consistency across devices is expected.

Note: The data in the `./data/mock.json` file is from [marvel developer api](https://developer.marvel.com/docs#!/public/getComicsCollection_get_6) you can review it to understand the response properties.
The application here in VitalBeats is built with following stack, among others:

- react-native (**no expo**)
- react-navigation
- redux
- immerjs
- redux-saga
- axios

Your excercise should include this stack (except for axios).
