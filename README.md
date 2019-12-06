## React Material Wizard

React-Material-Wizard is descriptive library based on material-ui, react-final-form and redux for creating huge amount of entities through the wizard. Redux state is being handled by the library so you don't need to worry about working with store.

### Features
1. Every wizard step is a standalone form that work with provided api.
2. You can always go back and do put (or specify to use any other api method) on an already fulfilled step, or you can disable step after it's creation so you will not be able to update it.
3. Specify dependencies between wizard steps, so you will not be able to proceed to the specific step before you are not fulfilled the list of required steps for that step.
4. Access the data of already fulfilled steps in another steps.
5. Specify side effects to be run after wizard step is being fulfilled.
6. With useful form helpers you can create multiple entities for single step at once (array of forms) and do forms nested.
