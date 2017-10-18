# pofiresa (POlymer, FIrebase, REdux, SAga)
A (hopefully) simple sample application that combines Polymer, Firebase, redux and redux-saga into something reusable. 

The main idea is to create a Polymer Starter Kit based web application sample, that demonstrates how
- [x] Polymer
- [ ] Firebase
- [x] Redux
- [x] Redux Sagas

can be combined in a useful way.

Since I'm in no way a Javascript pro the code is probably far from optimal and currently contains a mix of various coding styles.
Mainly because I'm teaching myself on the way and got inspiration from various blog posts and documentation sites:
* [Project Structure for Using Redux with Polymer 2.0](https://www.captaincodeman.com/2017/07/19/project-structure-for-using-redux-with-polymer-20)
* [Polymer Redux Documentation](https://tur-nr.github.io/polymer-redux/docs)
* [Redux-Saga Documentation](https://redux-saga.js.org/)
* [A Guide For Building A React Redux CRUD App](https://medium.com/@rajaraodv/a-guide-for-building-a-react-redux-crud-app-7fe0b8943d0f)
* [How to combine polymer-redux and \<app-route\>?](https://stackoverflow.com/questions/41440316/how-to-combine-polymer-redux-and-app-route/43479815)

## Implementation Roadmap
- [x] Basic Polymer, Redux and Redux-Saga setup 
- [x] Implement a fake loading mechanism (bind state via polymer-redux)
- [x] Integrate app-router with redux and add location to store
- [ ] Implement a generic navigation action
- [ ] Add sidebar state into redux store and toggle it via actions
- [ ] Integrate Firebase via Polymerfire
- [ ] Implement Firebase Query and display results (use redux-saga)
- [ ] Simple edit screen that uses Firebase Document
- [ ] Add Firebase authentication and add user to redux-store
