# FindYourBeer

## https://find-your-beer.herokuapp.com/

## Author: Jakub Mandra

## Admission

Here is the link to my app deployed on Heroku server: https://find-your-beer.herokuapp.com/
This app is a recruitment task - I can't publish my code solution.

## About:

Here are some user stories and requirements:
*	General requirements
  *	User should at all times know that something is being loaded (e.g. spinner/fake content)
  *	Application should be responsive and work both on desktop and mobile devices
  *	Use this API: https://punkapi.com/documentation/v2

*	Listing view
  *	User should see 20 beers on the first page
  *	Each beer on the list should display: name, image, tagline
  *	On bigger devices items should appear in a grid and on smaller resolutions they should wrap in a list
  *	User should be able to see more beers as she/he scrolls down (infinite scroll)
  *	If there are no more items to load user should see that’s the end of the list and no more requests should be triggered

*	Details view
  *	Details view should be a modal accessible by clicking on any item on the listing view or by manually entering the page using it’s URL address (e.g. /details/:id)
  *	The modal should contain the following informations: name, tagline, description, image, brewer_tips, ibu, abv
  *	Additionally modal should also list up to 3 similar beers (use available API to get beers with similar IBU/ABV/EBC)

## Technology stack:

* React (create-react-app)
* ES6
* Redux
* Node.js
* Styled-components
* ESLint
* Automated test of Redux (Jest)
