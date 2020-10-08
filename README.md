# Finixio - React.js tech test
## Intro

Thanks for your interest in Finixio! Our React.js technical interview process involves candidates doing an at-home (or at work, or at Costa) project to test your React.js knowledge and problem solving abilities, while also giving you a chance to write code in a way that you find comfortable.

This test should take about 1 hour. If you take less time, no problem! If you take more time, that's cool too but don't spend more than 2 hours working on this. Using Google/StackOverflow//whatever for help is allowed, but ultimately you should write and be able to justify every piece of the code being submitted.

Your solution should be shared on a public Github or Bitbucket repo showing all commit history.

## Task
Ravi is keen to diversify his investments into crypto currencies, but can’t decide which coin to purchase. Using React.js and the [free cryptocompare API](https://min-api.cryptocompare.com/documentation), pull a list of **10 coins** and display their `name`, `current price`, `opening price` and `price increase` (the percentage difference between the opening price and the current price, you’ll need to calculate this yourself from the available API data). To make Ravi’s selection easier, please default the table sorting by the price increase descending, showing coins with the highest price increase first. 

| Coin Name | Current Price (USD) | Opening price (USD) | Price Increase↓ |
|-----------|---------------------|---------------------|-----------------|
| BTC       | $10,610.98          | $10,600             | 0.104% ($10.98) |
| ETH       | $340.07             | $339.92             | 0.047% ($0.15)  |
| LTC       | $35.62              | $36.02              | -1.110% ($-0.4) |
| ...       | ...                 | ...                 | ...             |
| 10th coin |                     |                     |                 |


## Requirements
- Use ReactJS (`create-react-app` encouraged)
- You can use either Hooks or standard react, but in either case the correct use of state and props is required, as well as correct component abstraction (ie knowing when to make something a subcomponent)
- You should attempt to make your rendered table as close to the example as possible, deriving the calculations necessary to show the price increase
- This is not a UX test, focus on the functionality

## Bonus points
- Allow the user to specify the currency, and update the results accordingly
- Make the table columns sortable, feel free to use a table / UI library
- Cover your code with tests you think are most appropriate
