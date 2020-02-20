## Course link
This notes are about the course "Mocha Javascript Test Framework" on TAU: https://testautomationu.applitools.com/mocha-javascript-tests/

## Function Calls

We have to know about 2 functions calls. 

This are the following:

describe()
it()

### describe()
Is a simple way to group our tests in Mocha. It provides us a feature to create a series of tests. It takes two arguments: 

- name/description of the test group
- callback function: it needs to be executed after another function has finished executing

### it()
It is a way to describe the individual test case.

- Should be nested within the describe() block. 
- Should be described in a way that it makes sense for the given TC

### syntax:

describe ('Description of the Test Suite', function(){

    it('About the test', function(){
        // code to test the condition
    })
})

### Example output lesson 2

https://i.imgur.com/gygzWcI.png

Also there is an adittional need and it is to configure the package.json with the following:

{
    "scripts": {
        "test": "mocha"
    }
}

The file need to be called test.js, if not it wasnt working for me.
