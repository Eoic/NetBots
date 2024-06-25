[![Specification](https://img.shields.io/badge/GitBook-Specification-purple)](https://karolis-1.gitbook.io/netbots-project/)

# NetBots
Multiplayer real-time robot programming game for the web. 

### Table of contents
1. [About](#about)
2. [Getting started](#getting-started)
3. [Subrepositorties](#subrepositories)
4. [Specification](#specification)
5. [Contributing](#contributing)

### About
This is a parent repository of the project and intended to hold links to subrepositories where specific system parts are implemented, hold specification, documentation and other non-code files related to the project, if the aforementioned items are common to the entire system and not only to some specific part.

### Getting started
1. **Clone the repository**
  ```
  git clone git@github.com:Eoic/NetBots.git
  ```
2. **Initialize and update submodules**
  ```
  git submodule update --init --recursive --remote
  ```
3. **Install dependencies** <br>
  Navigate to each subrepository and follow the instructions provided in their respective `README.md` files to install any necessary dependencies.
4. **Run the project** <br>
  Each subrepository will have its own instructions for running the project. Follow the guidelines in the subrepositories to get the system up and running.

### Subrepositories
* [NetBots-Web](https://github.com/Eoic/NetBots-Web/tree/master) - landing page of the project.
* [NetBots-Server](https://github.com/Eoic/NetBots-Server/tree/master) - back-end server that handles the game logic.
* [NetBots-Client](https://github.com/Eoic/NetBots-Client/tree/master) - client side of the project which mainly deals with rendering the scenes.

### Specification
You can look up at the specification [here](https://karolis-1.gitbook.io/netbots-project/).

### Contributing
Not accepting contributions just yet.
