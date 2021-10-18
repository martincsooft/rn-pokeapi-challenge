# PokeApi app challenge for React-Native developers

The challenge is to create a basic react-native application consuming data from the PokeApi:

- URL: https://pokeapi.co/

## Screens and features

The app must have the **following screens**:

1. _MainScreen_: initial screen containing 2 buttons:
   - Search Pokémon: navigate to SearchPokemon screen
   - Random Pokémon: navigate to RandomPokemon screen
2. _SearchPokemonScreen_:
   - Should initially load a list of all Pokémon from gen 1 (from Bulbasaur to Mew) ordered by number (id) that shows the number, name and types of each item
   - Should have an input element to filter Pokémon by name or type (i.e., if you write “fire” you should only see fire type Pokémon, and if you write “fire flying” you should only see Pokémon with both types); also it should have a button to clear the filter. When pressing an item of the list it should open a modal component showing basic information of that Pokémon
3. _RandomPokemonScreen_:
   - It should load information of a random Pokémon (this time from every gen)
   - On the top, it should have a button to load another random Pokémon replacing the one already shown
4. _SplashScreen_: splash screen showing the Pokémon logo or similar

## Navigation

Navigation should be done using **react-navigation** and it should have a _Drawer Navigation_ component containing:

1. A **header section** showing the App name, and current date and time
2. A **list of the screens** to navigate (MainScreen, SearchPokemonScreen, RandomPokemonScreen)

## Tech Requirements

These are the following conditions for the development:

- The code should be using **react-native** (with or without Expo)
- The code should be written in **JavaScript**
- All the code and comments **should be written in English**
- Use a proper naming conventions and standards when defining the structure of the project and the name of variables, functions, etc.

## Extra Points

Extra points will be given if:

- The app features a **Redux** implementation
- **Dark/light theme** feature is applied

## Evaluation Criteria

The criteria for evaluation are (in order of importance):

1. App should **fully work** (all basic functionality must be achieved)
2. **Organization** (code and folders/files structure) and **componentization**
3. **Reusability** of code
4. General look and feel of the app (styles across the app must be consistent)

## Presentation

The result of this challenge should be presented as a GitHub public repository.

Please add some minimal documentation (in the form of a README file) describing how to build and/or run the project and if there is any requirement or consideration to do so.

Oh, and please don't fork this repo in order to create your own. That way other people trying to complete this challenge won't be able to see solutions to it 😆.

Let's code 💻!
