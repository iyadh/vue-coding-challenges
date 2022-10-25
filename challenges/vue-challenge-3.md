# Vue Challenge #3

### Requirements

In the given code, we replaced a computed property with a watcher.

When using computed properties we cannot control how often the property is recomputed, if the dependency changes, the computed property will recompute immediately. We cannot delay the execution of a 
computed property.

To accomplish our goal we need to implement a function that limits how often a particularly expensive operation can be run. In this case, we want to limit how often we access the dataset until the user has 
completely finished typing.

We can do that using watcher.

In the watcher we set a timeout that will execute our logic after specified amount of time (1000 ms in our case). Each time the search query changes (user types something in the input), we clear the 
previous timeout and set the isSearching flag to true, if no further change occurs within 1000 ms, we filter the list, isSearching flag to false and show the results.


### Starter StackBlitz
Please fork this link on [StackBlitz](https://stackblitz.com/edit/vitejs-vite-dureij)
