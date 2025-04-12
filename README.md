# FSND_Game_Design_API

## Project Overview

FSND_Game_Design_API is a RESTful API designed specifically for game developers. It provides essential endpoints and functionalities that streamline game design and development processes, making it an ideal tool for projects in the Full Stack Web Developer Nanodegree program. It includes a variety of features to assist in the development of games, such as user authentication, game state management, leaderboards, and more.

## Setup and Installation

To set up and install FSND_Game_Design_API, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/[username]/FSND_Game_Design_API.git`

2. Navigate to the project directory `cd FSND_Game_Design_API`

3. Install the required dependencies using `pip install -r requirements.txt`

Please note that this project requires Python 3.8 or later.

## Usage Examples

Once you have the API running, you can interact with it using HTTP requests. Here are some examples:

- To create a new game:
```
POST /games
{
  "name": "New Game",
  "description": "A description of the game",
}
```

- To get a list of all games:
```
GET /games
```

- To update a game:
```
PUT /games/{game_id}
{
  "name": "Updated Game",
  "description": "An updated description",
}
```

- To delete a game:
```
DELETE /games/{game_id}
```

## Contributing

We welcome contributions from the community. To contribute:

1. Fork this repository.
2. Create a new branch on your forked repository.
3. Commit your changes to your new branch.
4. Push your changes to your forked repository.
5. Submit a pull request to this repository.

Before submitting your pull request, please ensure your code adheres to the existing style to maintain consistency in the codebase.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.