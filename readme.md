## Getting Started

If you are running a Unix system with yarn installed you can copy the code below, otherwise replace with corresponding Windows/npm commands.

```sh
git clone https://github.com/coverse/js-test.git
cd js-test
yarn # npm i
yarn test # npm test
```

The tests will run with `mocha --watch` and should immediately fail.

Your task is to correct any errors and make all the tests pass.

## Instructions

### Setting up

  - Visit [coindesk.com/api](coindesk). Find "Historical BPI data" at the bottom of the page with instructions on composing the query
  - Make a request for prices between January 1, 2019 - January 31, 2019
  - Populate the params to complete the request

Once you enter the correct parameters, the first test should pass.

The following 4 tests each provide instructions and results required for solving them. They are as follows:
- TODO #1 - Return the sum of all values
- TODO #2 - Find the top value (Number) from any date
- TODO #3 - Extract only the results from Tuesdays
- TODO #4 - Return the top 5 dates in descending order

## Submitting the code

Once you have completed the code and passed the tests, you need to send only the contents of your `index.js` file. You can either:

- upload to a service (like Gist, jsFiddle, Drive) and send us the link
- copy the contents of the file in the body of your application, email, or chat

Once we've received your submission, we will send you our own solution to the task for you to review. If you are selected, we will contact you for a brief interview. You will likely begin with your first assignment right there and then.

[coindesk]: https://www.coindesk.com/api
