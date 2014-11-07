# Polymer and Firebase Demo
This project includes a set of Polymer components and a starter project,
designed to be used with the [Polymer tutorial](http://polymer-project.org/docs/start/tutorial/intro.html).

This project adds persistence storage with Firebase to the Polymer Starter Project.

# Try this out
1. If you don't already have Firebase, [Sign up](https://www.firebase.com/account).
  1. You will need your Firebase project ID - that's important!
  1. Also, make sure your Firebase is writable (no authentication demo here!) 
1. `git clone https://github.com/saturnism/polymer-firebase-demo`
1. `cd polymer-firebase-demo`
1. `bower install`
1. `vi post-service/post-service.html` and update the `location` attribute of the `firebase-element`
1. `python -m SimpleHTTPServer`
1. Open [http://localhost:8000](http://localhost:8000)

