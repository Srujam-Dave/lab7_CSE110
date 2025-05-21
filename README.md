# Lab 7

### Question 1

I'd run tests every time code is pushed. It's impossible to accurately tell whether tests are run locally,
or if code was modified after the tests were run. It's a terrible idea to only run tests after development,
since major errors could be left unnoticed or major structural issues could be added accidentally. Running
tests with every push ensures that tests are run, and ensures that tests are run with every incremental addition
to the codebase that all developers pull from.

### Question 2

I wouldn't use end-to-end testing for a function, since processing an input from an end-to-end test could require multiple different functions or components to work well (UI, backend, etc.). A unit test would work much better in this case.


### Question 3

The lighthouse navigation page analyses how quickly and efficiently the page loads, as well as accessibility, search engine optimization, and adherence to best practices **for the page load**. The snapshot page analysis the accessibility, performance, adherence to best practices, and search engine optimization for **an arbitrary page state**. 


### Quesiton 4

According to the lighthouse report, the page can be improved in the following ways:

1. The page should have a `<meta name="viewport">` tag to improve visibility on mobile devices.
2. The html tag should have a `lang` attribute to improve compatability with screen readers. 
3. The document should have a `meta` description with a summary to improve search engine optimization.