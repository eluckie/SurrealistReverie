#### Memory Lane

## Description
A React application that stores memories so we don't have to store them ourselves anymore. This app includes: 

* Full CRUD functionality with hooks and Firestore.
* User authentication and basic authorization.
* Routing with react-router.
* Ability to associate memories with specific users.

## Technologies Used:


## Project File Planning:
App
Router
  Header/
  Routes
    /signin
    SignInForm (login and register)
    MemoryControl?:

    /home
    logged in:
    (MemoryInputForm
    OR
    /home/memories
    MemoryList
      /home/memories/memoryID
      MemoryDetail)
    not logged in:
    "you're not logged in!"

    /Routes
  Footer
/Router

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Known Bugs

## License

_[MIT](https://opensource.org/license/mit/)_

Copyright (c) _2023_