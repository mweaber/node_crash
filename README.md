<!-- Start of a Node crash course -->

Node.js is a JavaScript runtime (not a language or framework)
Written in C++

Good things to know:

    JS Fundamentals:
        Objects, Arrays, Conditional

    HTTP (status codes, headers)
    JSON (JavaScript Object Notation)
    Arrow Functions
    Promises
    MVC Pattern (Model, View, Controller)

Why use Node?

Fast and efficient and highly scalable
Event driven, non-blocking I/O* 
Popular
Full stack (MEAN, MERN)

*Non-blocking I/O
    Works on a single thread using non-blocking I/O calls
    Supports tens of thousands concurrent connections
    
    Async

Node good for most to all projects....anything that is not CPU intensive

REST API, CRUD, Tools Utils

-------------------NPM--------------------
Node Package Manager
node_modules
package.json


npm init --- generates package.json file
npm install xxxxx --- install package



============Deploy to Heroku==========

heroku --version [to verify cli installed]

heroku login [logs into heroku]

heroku create [creates the heroku git repo]
    once this has finished you'll have a https://sheltered-peak-63181.herokuapp.com/
    link to go to. Go to the deploy tab and copy the heroku git:remote -a sheltered-peak-63181

git push heroku master [pushes to heroku]