# TODO: Implement Search Message for Toyota Cars

## Tasks
- [ ] Add search message div in HTML near mobile search bar
- [ ] Modify JavaScript search logic for mobile search button to show message when searching "mobil toyota" and no results found
- [ ] Test the functionality by searching "mobil toyota"

## Information Gathered
- index.html contains a mobile search bar with input id="mobileSearchInput" and button id="mobileSearchButton"
- Search functionality maps search terms to car types and redirects to model.html
- CSS class .search-message is available for styling error messages
- When no matching car is found, currently redirects to model.html with search parameter

## Plan
- Add a div with id="searchMessage" after the mobile search bar to display the message "mobil yang anda cari tidak tersedia"
- Modify the mobile search button click handler to check if search term includes "mobil toyota" or "toyota" and no car type is found, then show the message on the page instead of redirecting
- Hide the message before each new search attempt

## Dependent Files
- index.html (only file to be edited)

## Followup Steps
- Test searching "mobil toyota" to ensure message appears
- Test searching other terms to ensure normal redirect behavior
- Verify message styling and positioning
