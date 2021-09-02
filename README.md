# Alphabet grid problem

[![CircleCI](https://circleci.com/gh/scottfrasso/alphabet_grid/tree/master.svg?style=shield&circle-token=04050410d5c8ad6cbe476a9f47dbb91ec1ab3b64)](https://circleci.com/gh/scottfrasso/alphabet_grid/tree/master)

# The problem

This problem involves finding the longest possible word in the alphabet grid below. Legal moves include moving up,
 down, left, and right. As well as wrapping around going from A to E or A to U, and so on.

ABCDE<br/>
FGHIJ<br/>
KLMNO<br/>
PQRST<br/>
UVWXY<br/>

### Running the example

1) Make sure you have node installed. I used node v10.8.0
Note: The only third party libraries used are for unit testing.

2) Run the example:

npm start

### Running the tests

1) To install the libraries used for unit testing

npm install

2) To run the tests use:

npm test

This uses mocha to run the tests and chai as the assertion library.

### English dictionary

The etc/large_dictionary.txt file here was taken from:
 http://www-01.sil.org/linguistics/wordlists/english/