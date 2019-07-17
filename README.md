# :construction: IAPPS Web App Front-End

Open source React and TypeScript setup to quickly get started with a project.

## DO NOT ADD ANY EXTERNAL LIBRARIES

Everything needed to develop the project has been setup properly including routing, css libraries, liniting files, build process. DO NOT add any external library without discussion. Please simply take a pull from develop and start adding HTML, CSS and TypeScript Code.

## Collaboration Guidelines :checkered_flag:

### Code Quality :art:

* No class based Components. Use [hooks](https://reactjs.org/docs/hooks-overview.html#state-hook) only.
* No implicit types. To ensure the code is of the highest quality, use explicit types when declaring interfaces.
* Always develop the individual component in isolation using [React Storybook](https://storybook.js.org/). Do not add components directly to app. Check for all possible inputs and scenarios in storybook first.
* Always use [code splitting](https://facebook.github.io/create-react-app/docs/code-splitting) using ```React.lazy``` and ```React.suspense```
* Make sure to use [error boundaries](https://reactjs.org/docs/error-boundaries.html#introducing-error-boundaries)
* Justify every single line of code you write. If you don't know what your code is doing or why did you include it, it will be removed.
* Use [CSS modules](https://facebook.github.io/create-react-app/docs/adding-a-css-modules-stylesheet) only. No global CSS is allowed. Every component should be responsible for its own presentation.

### Testing :white_check_mark:

* The testing suite has been configured and setup. You just need to write your tests.
* A combination of [JEST](https://jestjs.io/) and [React Testing library](https://testing-library.com/docs/react-testing-library/intro) should be used for component testing.
* [Cypress](https://www.cypress.io/) will be used for end-to-end testing.
* Pull Request for individual components will not be merged without passing JEST tests.
* Pull Request for completed features will not be merged without end-to-end testing with Cypress.

### Project structure :card_file_box:

* The project directories has been setup using official react guidelines found on [this page](https://reactjs.org/docs/faq-structure.html). Please be sure to follow to directory structure to ensure that everything can be located by at a single glance.

## Tooling :wrench:

The follwing tool chain has been chosen keeping in mind the speed of development, code quality, validations, security and a minimalistic bundle size. Please DO NOT add anything else.

I have not yet decided on whether to use Redux or not. I'm more inclined towards MobX. If you can come up with a valid argument as to why we should use Redux, I'm all ears.

* TypeScript
* React Storybook
* React Router
* Formik
* Yup
* Styled Components
* PurgeCSS
* React Helmet
* JEST
* React Testing library
* Cypress
