# Funciton Pokedex

Functional description

## Getting Started

You will only need a browser and creating a user to access to your pokedex.

### Prerequisites

You don't need to install anything, just run the application on a browser.

### Installing

You don't need to install anything, just run the application on a browser.


## Running the tests

The application has automated test, so they may be run when necessary.
For example in case the application is evolved, test may be run.

## Application

The application welcomes the user by showing two main options, login a register.
If the user exists, it may login. In case it does not exist, it should register previously.

### Login
As soon as the user has logged in, userId and token are stored in sessionStorage.


## Home

As soon as the user has logged in.
The application has three main options:
* Logout
* Search
* Favorites



### Logout

Logouts the application. User Id and token are removed from sessionStorage.

### Search
It allows to search a pokemon by name, the results are shown below. User may scroll if necessary.

### Favorites
It allows to display a list of your favorite pokemon.


## PokemonCard

PokemonCard has four main parts.
* Card
* Display of the pokemon
* Pokemon Name
* More
    * Allows to see the detail of the pokemon (it also works clicking over card.)
* Favorites icon
    * Allows to add/remove to favorites.

## Detailed Pokemon
* Shows the stats and information, such as abilities, types, moves and held items, of the selected pokemon.


# Authors

* Marc
* Ury
* Carlos