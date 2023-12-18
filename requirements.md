# Requirements

## Vision
<!-- Minimum Length: 3-5 sentences -->
<!-- What is the vision of this product?
What pain point does this project solve?
Why should we care about your product? -->
The vision of this project is to give futbol fans an app to stay current on futbol related news, standings, and schedules. Users can customize their experience by creating a profile with user input, which helps show news relevant to their favorite team(s). This will help alleviate pain of futbol fans not knowing where to go to get their futbol news. Futbol is the most popular sport in the world with the most followers, and this app is to serve all the fans worldwide with futbol related news.

## Scope (In/Out)

## IN - The App Will Provide
<!-- Describe the individual features that your product will do.
High overview of each. Only need to list 4-5
Example:
The web app will provide information to the users about all the different Cat Cafe’s in the area
The web app will provide both walking and driving directions to each of the destinations
Users will be able to “Star” their favorite shops.
Each shop will contain reviews of the customer’s experiences -->

- Users can save their favorite teams and leagues
- Ability to filter on teams and leagues based on user preferences
- Statistics to the users about past matches
- Information to the users about future matches
- News and highlights

## OUT - The App will not provide
<!-- These should be features that you will make very clear from the beginning that you will not do during development. These should be limited and very few. Pick your battles wisely. This should only be 1 or 2 things. Example: My website will never turn into an IOS or Android app. -->
- It will be browser based and not be an iOS or Android app

### MVP

- User can log in and create a user profile to customize their experience
  - Upload photo link
  - Form to collect user information and preferences (favorite team, etc.)
  - User selects their preference in name of the sport: football, fútbol, soccer
- When the user is logged in, they can view and edit a dashboard of customizable statistics
  - Use a database to store which teams, players, or other datasets are in the user's dashboard
- Searchable/filterable list of statistics by team
- Information feed of upcoming matches sorted by location
- Users can like their favorite teams and be able to see the number of likes.
- 3rd Party API accessed to create custom database of sports information
- External server to host back-end
- External database to store user information (securely)
- Store data in cache so that 3rd party API does not have to be pinged if data is not "stale"

### Stretch

- Connect with other users who follow the same team
- Let the user follow their favorite players and teams with updated news.
- chat feature during live games to interact with other fans.
- Link to buy tickets for games (use a 3rd party API?) (SeatGeek, ticketMaster?)
- Video/audio/text highlights of game and players
- User can save their favorite player and see stats related to them

## Functional Requirements

- A user can save their favorite teams and leagues
- Ability to filter on teams and leagues based on individual user preferences
- Ability to view statistics about past matches
- Ability to view schedule for future matches

## Non-Functional Requirements

- Security: Authentication of user
- Usability: Simple interphase to filter on favorite teams and leagues