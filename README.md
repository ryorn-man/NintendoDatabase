# Nintendo Database

## Overview
The Nintendo Database collects data and displays information about entities related to Nintendo. It consists of a database running on mySQL, and a PHP website with an encyclopedia design. The database contains entities related to Nintendo, as well as articles and other content displayed on the website. The site is similar to a wiki, but much simpler to design; there is no need to program functions for editing, logging in, adding and deleting pages, or all that other user-centric stuff that makes a wiki a wiki.

The main purpose of the Nintendo Database is to inform users about the company Nintendo. It provides information on products, services, the timeline of the company, people working at Nintendo, and other relevant details, as identified in the paragraph below.

There are two general categories of database entities: entities related to Nintendo, and website content for users to read. The first category consists of video games, consoles, franchises, magazines, toys, mobile devices, historical events in the company timeline, services offered by Nintendo, subsidiaries and business partners, and staff members working at Nintendo or associated companies. The second category includes articles and images.


The user interface of the website is simple and minimalistic, to make for an easy reading experience. There is a header with a logo, navigation menu, and (if time allows) a search bar. Articles reside in the page body, with a sidebar for links to header elements. There are references for information at the end of each article. There are description boxes for games, consoles, magazines, etc. which draw information from the database.

 Many resources can provide information to aid this project. There are many pieces of free and open-source software available for creating wikis, such as MediaWiki (used by Wikipedia), Wiki.js, PHP Wiki, and Nuclino. While the Nintendo Database is not a wiki, the design and source code of these projects may offer clues for how to structure the site and handle internal linking. Wikis typically store their articles in a database. There is also a massive amount of information available online about Nintendo.
 
It should be possible to complete this project in three months.

## Wireframes

![alt text](/images/Wireframe.jpg)

## Entity Relationship Diagram
![alt text](/images/ERD.jpg)

## Class Diagram
![alt text](/images/ClassDiagram.jpg)

## Table of Requirements

| Requirement | Description                                                                  | 
|:-----------:|:-----------------------------------------------------------------------------|
|      1      |The application allows users to view information on Nintendo-related entities: video games, consoles, franchises, magazines, toys, mobile devices, historical events in the company timeline, services offered by Nintendo, subsidiaries and business partners, and staff members working at Nintendo or associated companies.|
|      2      |The application contains a database with two categories of tables: Nintendo-related entities, and website content.|
|      3      |The application's user interface is a PHP website which connects to the database.|
|      4      |The application contains a search function.|
|      5      |The application contains internals links between pages.|

## User Stories

Story 1: A user opens Nintendo Database and reads about every Nintendo game on every system.

Story 2: A user opens Nintendo Database and learns about the history of the company.

Story 3: A user opens Nintendo Database and learns about every Nintendo console ever made.

Story 4: A user opens Nintendo Database and learns about every Mario and Zelda game.

Story 5: A user opens Nintendo Database and learns about magazines created by the company.

## Use Cases

### Use Case 1: Bob learning about Mario
System: Windows computer
Stakeholder: Bob
Use case goal: Learn about the Mario games
Primary actor: Bob
Preconditions: Windows computer, Interest in learning about Mario
Basic flow: Bob opens up Google Chrome, goes to Nintendo Database, and clicks on the "Franchises" and then "Mario" links, where he reads about all the Mario games.

### Use Case 2: Trisha scrolling while bored
System: iPhone
Stakeholder: Trisha
Use case goal: Alleviating boredom
Primary actor: Trisha
Preconditions: iPhone, Boredom, interest in Nintendo
Basic flow: Trisha is bored at work. She opens Safari, and continues reading the entry on "F-Zero GX" that she started the previous night. She scrolls down through the page. Afterward, she presses "Consoles" in the navigation bar, selects "Nintendo Switch", and reads about the Nintendo Switch. She taps a link and reads about <i>Mario Kart 8 Deluxe</i>, the best-selling game on the Nintendo Switch.

### Use Case 3: George deciding which games to buy
System: Windows computer
Stakeholder: Bob
Use case goal: Decide which games to buy for his kids
Primary actor: George
Preconditions: Windows computer, Bought his kids a Nintendo Switch
Basic flow: George bought his kids a Nintendo Switch for Christmas, and is trying to decide which games to buy. He opens up Nintendo database and reads about many games by finding them through the "Franchises" and "Games" pages, and the entry for "Nintendo Switch" under "Consoles". He decides to buy <i>The Legend of Zelda: Tears of the Kingdom</i>, <i>Pokemon Violet</i>, and <i>Resident Evil 4</i>.

### Use Case 4: Albert reading about the history of Nintendo
System: Windows computer
Stakeholder: Albert
Use case goal: Learn about the history of Nintendo
Primary actor: Albert
Preconditions: Windows computer
Basic flow: Albert wants to learn about the history of Nintendo. He opens Nintendo database and clicks "Company History" in the navigation bar. From there, he reads about the company's history.

### Use Case 5: April learning about Zelda
System: Windows computer
Stakeholder: April
Use case goal: Learn about the Zelda games
Primary actor: Bob
Preconditions: Windows computer, Interest in learning about Zelda
Basic flow: Bob opens up Google Chrome, goes to Nintendo Database, and clicks on the "Franchises" and then "Zelda" links, where he reads about all the Zelda games.

## Use Case Diagram

![alt text](/images/UserCaseDiagram.jpg)

