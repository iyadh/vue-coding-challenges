# Vue Challenge #4

The goal of this challenge is to consume a given public API to build an interactive interface around it.

We'll go with **[CoinGecko API](https://www.coingecko.com/en/api)** and develop a Crypto Monitoring Dashboard.


# Stack

The recommended stack is:

 - Vue 3 (Composition API)
 - Pinia
 - Modern CSS (Tailwind is a plus)
 - Typescript (a must)
 - Vue Router

## Requirements

### Main Page
When accessing the main page, a user should be able to see non filtered list of crypto currencies and their price in a given real world currency (USD, EUR, GBP, CAD, BTC, ETH).
The user should be able to:
- Filter by name, category
- Paginate through the results (filtered and unfiltered)
- Sort the listing by: name, price, market cap
- Add a given crypto currency to favorites
- change currency (USD, EUR, GBP, CAD, BTC, ETH)
- select a cryptocurrency and view its details

No need to display all data per crypto in this page, only: Thumbnail, Name, Price, Category, Market Cap, Total Volume, Price changein 24h, 7 days price variation chart, and an add/remove favorite.

### Favorites Page
When accessing `/favorites` route, a user should be able to see a list of the cryptocurrencies he added to favorites, and can apply the same actions as in main page.
The user should be able also to remove a cryptocurrency from his fav list.
No need to display all data per crypto in this page, only: Thumbnail, Name, Price, Category, Market Cap, Total Volume, Price changein 24h, 7 days price variation chart, and an add/remove favorite.
**Bonus (not mandatory)** Add the ability to rearrange the favorites list.

### Single Cryptocurrency page
When accessing `/view-crypto` route, a user should be able to view a given cryptocurrency informations. He sould be able to see if it is added to his favorites or not, add or remove it to favorites and switch between currencies (USD, EUR, GBP, CAD, BTC, ETH) to see the price.

### Other Requirements
You should manage several uses cases where:

 - informration is not available
 - empty state
 - search query is empty
 - 404
 - etc

A user should be able to see a chart for each cryptocurrency showing price variation to the selected real currency.
Changing the price currency should be reflected on all pages.

## Evaluation Criteria

 - Clean code
 - Code Typing
 - Store structure
 - Pagination
 - Data flow
 - UI Design

