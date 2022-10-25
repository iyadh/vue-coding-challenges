# Vue Challenge #1

The goal of this challenge is to consume a given public API to build an interactive interface around it.

We'll go with **Rick and Morty API** and develop a real time character database.


# Stack

The recommended stack is:

 - Vue 3 (Composition API)
 - Pinia
 - Modern CSS (Tailwind is a plus)
 - Typescript (a must)

## Required views

### Characters Listing
When accessing `/characters` route, a user should see an interface where he:

 - can search characters by: name, status (alive, dead or unkown) and can reset the search form
 - can list characters
 - can switch between pages (pagination should change according to search query)

### Single Character Page
When accessing `/character/:id` route, a user should see an interface where:

 - manage navigation (back button for instance)
 - information about given character

### Other Requirements
You should manage several uses cases where:

 - informration is not available
 - search query is empty
 - 404
 - etc

## Evaluation Criteria

 - Clean code
 - Code Typing
 - Store structure
 - Pagination
 - Data flow
 - UI Design

