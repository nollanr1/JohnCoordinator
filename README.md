# JohnCoordinator
An a way to coordinate "Everyone Is John" games over the internet.

The intent of this project is to provide a simple character sheet for playing games of "Everyone is John" as described in the [rules given by Michael Sullivan](https://rtwolf.github.io/Everyone-is-John/).

The roadmap for this project is as thus:
- Initialize project plan  **<-- Currently *here***
- *V1 Release:* Static sheet for tracking a player's traits and points
- *V2 Release:* Local storage for character sheet so a given sheet can be saved and returned to at a later time
  - *Possibly add support for saving multiple characters instead of just one*
- *V3 Release:* Linking character sheets to a GM so the GM can see the state of all the players at once.
- *Stretch Goal:* Persistent storage so full games can be stored and then resumed later

The stretch goal is labeled as such because storage of any significant size is not free, and I don't want to spend any money on this project. So it'll likely be a hodge of local storage with a game key stored in the cloud that the players can use to coordinate.
