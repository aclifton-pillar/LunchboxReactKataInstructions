# Lunchbox React Kata

This kata will build your skill with the following in the React framework:

* Toolchain Installation and Use
* Creating Views
* Retrieving Data from an Endpoint
* Acceptance Test Driven Development
* Unit Test Driven Development

## Instructions

When you complete this kata, you will have completed the following:

* Set up your development environment
* Create a new React project
* Create full unit test coverage on a single view
* Create an acceptance test using the following Gherkin:
    * Given a number web service that returns 6 in a JSON object
    * When I click the FizzBuzz button
    * Then I see Fizz
* Work with a single view UI
* Test drive the complete FizzBuzz logic

### Development Environment
[Installing Node.js with NVM](https://gist.github.com/d2s/372b5943bce17b964a79)

[Installing yarn package management etc](https://yarnpkg.com/lang/en/docs/install/#mac-stable)

[Installing detox for acceptance tests](https://github.com/wix/detox/blob/master/docs/Introduction.GettingStarted.md)

### React Project Setup
[Brief React Installation Instructions](https://reactjs.org/docs/add-react-to-a-new-app.html)

### Unit Testing with Jest
[Testing React with Jest](https://facebook.github.io/jest/docs/en/tutorial-react.html)

Note that, out of the box, yarn+watchman will watch for changes to your project and re-run
tests around changed code.  You can also instruct it to re-run all tests by type 'a' in
the terminal window where you ran 'yarn test.'

Also note that you will probably have to do 'npm run eject' to do custom configurations
of Jest, such as specifying a setup file to be run before tests.  It's not scary, though.
Just make sure to do a 'yarn install' afterward so it'll install the millions of 
dependencies you were getting for free before.

### Acceptance Testing with ??? (and a fake server)
We are currently spiking on our preferred acceptance testing solution.

### Working with a View
For this app, you can do all your work App.js.  It will be your single view in the app.

Notice that it is a class that extends Component and, like every Component, it has a render
method.  You can add other methods to it to retrieve data, do calculations, etc.

### The Magical Wonder of FizzBuzz
FizzBuzz is a deceptively simple programming problem used by countless
IT recruiters to find out if candidates indeed have at least some of the
programming skills they claim.  You can implement it in almost any form
of computer language in no more than a couple minutes.  If you can provide
input to a function, display the output, and write a couple if-thens, you 
can complete FizzBuzz.

Here are the rules:
* Given an input integer
    * If the integer is divisible by 3, return or display Fizz
    * If it is divisible by 5, return or display Buzz
    * If it is divisible by both, return or display FizzBuzz
    * Otherwise, just return the display the input number
    
But wait!  Don't just fixate on a bunch of if-elseif-else stuff.  In interviews,
FizzBuzz can be an opportunity to show your technical depth.  How would you
thin slice this problem?  Is there more than one way?  How would you test
drive it?  What kinds of tests give you the best value?

And, for the implementation itself, what happens if you can't use if blocks?
Does the implementation language give you other structures you can use?
What happens if a number is divisible by both 3 and 5?  Is there any point
in checking for 3 and 5 individually?  

How could you write the code in an
OO style?  A functional style?  Could you write code that would do the
evaluation using only binary logic operators?  What if you need to evaluate
billions of numbers really fast in a stream?  How could you parallelize the
operation?  Does knowing the answer to one number make it easier to find
the answer for another?  What are the characteristics of your function?
Does it run in constant time?  Why or why not?

The point is that there's a wealth of opportunities to explore the whole of 
computer science, even with such a simple program.  So enjoy doing this
implementation and let it fill your mind with ideas.

