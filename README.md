# js-browser-environment
Trys to implement all Chrome browser API's in a Environment Agnostic way.


## Idea
Browsers are secure by design. Server Side JS is insecure by design and has low level system access. execute scripts in browser like js environments via offering the same API's as a browser without access to the low level system api's. 

- [ ] implement webWorkers can get access to low level system functions via passing messages.
- [ ] implement fetch fully browser compatible inside webworkers
- [ ] implement serviceWorkers can listen for fetch events.
