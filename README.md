# 🏗️ Create a Command Line Auction App

- Within your groups you are going to be creating a Node application called "Great-Bay" which allows users to create and bid on assorted items, tasks, jobs, or projects.

- The basic application is fairly simple: Upon loading up the program, the user is prompted on whether they would like to "POST AN ITEM" or "BID ON AN ITEM"

- If the user selects "POST AN ITEM" they are prompted for an assortment of information regarding the item and then that information is added to the database so that others can bid on it

- If the user selects "BID ON AN ITEM" they are shown a list of all available items and then are prompted to select what they would like to bid on. The console then asks them how much they would like to bid, and their bid is compared to the previous highest bid. If their bid is higher, inform the user of their success and replace the previous bid with the new one. If their bid is lower (or equal), inform the user of their failure and boot them back to the selection screen.

## 💡 Hints

Consider some of the following questions while planning your approach:

- How will the app track the highest bid?
- How will users choose an item to bid on?
- What default values if any will an item need?

It is often much easier to first get a test query working using MySQL Workbench or the MySQL shell before implementing the query in the JavaScript.

## Screenshots

### Main Menu

<img alt="main menu" src="./Images/00-main-menu.PNG" width="500">

### Post Item

<img alt="post item" src="./Images/01-post.PNG" width="500">

### Bid on Item

<img alt="bid item" src="./Images/02-bid.PNG" width="500">

### Bid to Low

<img alt="low bid" src="./Images/03-bid.PNG" width="500">

### Bid Accepted

<img alt="big accepted" src="./Images/04-bid.PNG" width="500">

## Bonus

- Once your group has put together the basic application, it's time to test your collective skills on some additional functionality, or "addons". Remember to take into consideration the amount of time you have been given when choosing what addons you would like to tackle.

- Create a sign up and login system that prompts users for a username and password upon loading up the app. **Do not worry about setting up a truly secure database if you choose to tackle this addon. Just worry about building working sign up and login features.**

- Create a system on the "POST AN ITEM" which allows users to look at the auctions they have created. On this screen they can add new auctions, modify previous auctions, or close bidding on an auction.

- Create a system which allows users to view all of the auctions of which they are the leading bidder.

- Create a third option on the main screen which allows administrators to modify the database as they see fit.

- Create visually appealing tables. This means making dynamic console code and it is a lot harder than it might seem at first so do not think this one is so simple.

- Create a search function that allows users to look through the database of available auctions to find those that share the specified keyword or username.

- Get creative! There are a lot of addons to this app which you could create so feel free to work with your group to come up with something not listed above!
