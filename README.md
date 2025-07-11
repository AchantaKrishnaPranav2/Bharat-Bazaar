# Bharat_Bazaar

A Basic Trade game implemented in Python, featuring Indian cities, stations, and chance events.

This is a command-line multiplayer game where players can buy properties, pay rent, and try to bankrupt their opponents.


### Key Features

### Multi-Player Support
- Supports 2 or more players
- Players can choose their names

### Dice Rolling
- Has two Die (2-12)
- Players move in a 40-tile board

### Indian Properties
- Board includes Indian cities, airports etc
- Jail, Free Parking, Income Tax, Chance, Community Chest, Go to Jail

### Property Buying and Rent
- ₹200 per property
- ₹50 is the rent if a person falls on other persons property

### Start Bonus
- Players receive ₹200 when they pass "Start" 

### Win mechanism
- Players who cannot pay the amount are declared Bankrupt and are removed from the game
- The last player to remain wins

### Jail Mechanism
- one turn is skipped when landed on "Jail"

### Chance Cards
- Landing on a Chance tile activates one random event:
  - Income Tax Refund: Collect ₹50
  - Speeding Fine: Pay ₹50

### Player Actions
In each turn, a player can:
- Roll the die
- Declare bankruptcy
- View the owned properties


## Technical Highlights

- Object-Oriented Design with `Player` class
- Property pricing and rent handled via dictionaries
- Modular structure with reusable functions
- Clean input handling and error checks
- Easy to expand with features like houses, trading, GUI, save/load

## Future Improvements

- Adding a properties Class
- Induvidual prices and rents for each property
- House meachanism
- double the rent when you own all the properties of a colour

---

## How to Run
- visit https://colab.research.google.com/drive/14U94XnuXYbdzSuSQmo9Pa2_nqGfkQ5Al?usp=sharing to run the code


```
python bharat_bazaar.py
