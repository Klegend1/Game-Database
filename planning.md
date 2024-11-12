Project 3

App Name: Game Database (Might Change later)

Link https://rawg.io/apidocs

https://www.destructoid.com/wp-content/uploads/2022/12/global-game-market-2022-downloads-sales.jpg (Also will change later)



A game database used to store, manage, and retrieve data related to a video game. It serves as the backbone for various game features like player profiles, game states, inventories, achievements, leaderboards, and more. Game databases are essential for both online and offline games, particularly for multiplayer or persistent world games where data needs to be saved and accessed frequently.

As the user you will be able to access a library of some of the hottest games along with upcoming games. sort of like the PS & XBOX Store with all of the basic information.
 

# Functionality 

- Handle Rating, removing, and displaying games.

- Instructions for setting up a simple HTML interface to add create decks.

- Using Tailwind for styling.

1. Basic Game Information Stored in Databases
A typical game database contains the following key pieces of information about each game:

- Game Title: The name of the game.
- Release Date: When the game was released to the public.
- Genres: The genre(s) of the game (e.g., RPG, Shooter, Puzzle, etc.).
- Platform(s): The platform(s) on which the game is available (e.g., PC, Xbox, PlayStation, Switch, mobile, etc.).
- Ratings: User or critic ratings of the game (e.g., Metacritic score, user reviews).
- Developer: The studio or company that developed the game.
- Publisher: The company that published the game.
- Description: A brief summary of what the game is about.
- Price: The cost of the game, which can vary based on region or edition.
- Availability: Whether the game is available for digital download, physical purchase, or both

Schema for Database
NavBar, ImageSlider,
- Game Name
- Rating
- Genre
- Store




 
1. Player Account and Profile Management
Registration and Login: When you create an account, your personal data (username, password, email) is stored in the game’s database. Every time you log in, the game queries the database to check your credentials and load your profile.
Settings and Preferences: Any preferences you set within the game (graphics settings, control configurations, language choice, etc.) are likely stored in the database so that the game can remember them across sessions.


2. Player Progress and Achievements
Saving Progress: The game might store your progress in various ways, such as the levels you've completed, the items you've collected, or your character’s current state. For example, in a role-playing game (RPG), your level, experience points, and inventory are all stored in the database so that when you return to the game, your progress is intact.
Achievements and Trophies: Many games track special milestones or achievements, like completing certain tasks or winning trophies. This data is saved in the database, and the game displays your achievements each time you log in.

3. Game Economy and Inventory
Item Management: If you have an inventory of items, weapons, or currency in a game, all of that data is stored in the game’s database. For example, if you buy or find new items, the database is updated to reflect your new collection.
Transactions: In multiplayer or online games, when you trade, buy, or sell items, the game will update your inventory in the database. Similarly, in games with in-app purchases, the game’s database tracks your purchases and available currency.

4. Leaderboards and Rankings
Competitive Play: In multiplayer or competitive games, your performance, such as scores, wins, and other metrics, might be stored in a leaderboard database. This allows the game to display rankings and compare your performance with other players.
Global or Local Leaderboards: These rankings can be global (across all players) or local (among your friends or region). The database keeps track of the players who have the highest scores, fastest times, etc.

5. Multiplayer Data
Matchmaking: In online multiplayer games, the database plays a role in matchmaking by storing your player profile, rank, win-loss record, and other stats. This data helps the system match you with players of a similar skill level.
Session Data: During a game, especially in persistent-world games (e.g., MMOs), the game’s database keeps track of your session’s data—what you're doing in the world, who you're interacting with, and what resources you're using. This data is updated regularly to reflect your actions.

6. Real-Time Interaction
Events and Updates: If the game has live events (such as seasonal updates or special quests), the game database holds information about these events. Your participation and progress in these events are tracked in real-time.
Dynamic Content: In some games, your interactions with the game world might affect the database. For example, if you defeat a major boss or complete a complex quest, your action is logged in the database, and it could trigger in-game changes, like unlocking new content.

7. Player Behavior and Analytics
Game Analytics: Game developers often use databases to track player behavior (e.g., how long you play, what choices you make, where you spend your time in the game). This data helps them improve the game, balance gameplay, and create new content based on player preferences.
Feedback and Bug Reporting: Some games store bug reports, feedback, and user-generated data in the database, which may be reviewed by the developers to improve the game experience.

8. Security and Data Privacy
Account Protection: Your personal data, login credentials, and game-related information are stored securely in the database. Many games use encryption to protect your sensitive information, such as your password or payment details, ensuring your privacy and security.
Cheating Prevention: Some games store data about players’ actions (e.g., movement patterns, scores, etc.) to detect cheating or unusual behavior. This data helps developers identify hackers or players who exploit the game unfairly.

9. Offline vs. Online Games
Offline Games: If you're playing a single-player offline game, the database might be stored locally (on your device). Your progress, save files, and settings are stored in local files, which the game accesses each time you play.
Online Games: In online games, the game database is typically hosted on remote servers. This means your game data is synced across multiple devices (e.g., playing on different computers or consoles), and your progress is saved in the cloud, making it accessible wherever you log in.


Technologies used:
 - API (Rawg)
 - Tailwind
 
 