# Ionic-Vue-Incorrect-Activated-Route-State

This basic code repo shows a bug with the ionic tabs when using vue-routers's `replace` method. If a route is not on the tab bar but is defined as a child route of the tabs component, when transitioning to the route it doesn't remove the activated state off the current tab.

## To Replicate:
- Pull the repo
- Run `ionic serve`
- Click the 'Goto tab 3' button
- Note how the tab 1 route is still highlighted.
