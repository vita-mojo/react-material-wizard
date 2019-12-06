## React Material Wizard

React-Material-Wizard is a descriptive library based on Material-UI, react-final-form and redux for creating a huge amount of entities through the wizard. Redux state is being handled by the library so you don't need to worry about working with the store.

### Features
1. Every wizard step is a standalone form that works with the provided API.
2. You can always go back and do put (or specify to use any other API method) on an already fulfilled step, or you can disable step after it's creation so you will not be able to update it.
3. Specify dependencies between wizard steps, so you will not be able to proceed to the specific step before you are not fulfilled the list of required steps for that step.
4. Access the data of already fulfilled steps in other steps.
5. Specify side effects to be run after the wizard step is being fulfilled.
6. With useful form helpers, you can create multiple entities for a single step at once (array of forms) and do forms nested.
