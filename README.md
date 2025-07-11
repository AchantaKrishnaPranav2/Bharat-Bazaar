# Bharat_Bazaar

A Basic Trade game implemented in Python, featuring Indian cities, stations, and chance events.

This is a command-line multiplayer game where players can buy properties, pay rent, and try to bankrupt their opponents.

---

### Key Features

### Multi-Player Support
- Supports 2 or more players
- Players can choose their own names

### Dice Rolling
- Simulates rolling two 6-sided dice (2–12 total)
- Moves player around a 40-tile board

### Indian Property Board
- Board includes Indian cities (e.g., Mumbai, Hyderabad), airports, stations, and utilities
- Special tiles: Jail, Free Parking, Income Tax, Chance, Community Chest, Go to Jail

### Property Buying and Rent
- Properties can be bought for ₹200
- Landing on another player’s property requires paying ₹50 in rent
- Ownership and assets tracked individually

### Start Bonus
- Players receive ₹200 when passing the "Start" tile

### Bankruptcy System
- Bankrupt players are removed from the game
- Last remaining player wins

### Jail Mechanic
- Skips one turn when landed on "Jail"

### Chance Cards
- Landing on a Chance tile activates one random event:
  - Income Tax Refund: Collect ₹50
  - Speeding Fine: Pay ₹50

### Player Actions
Each turn, a player can:
- Roll the die
- Declare bankruptcy
- View owned properties

---

## Technical Highlights

- Object-Oriented Design with `Player` class
- Property pricing and rent handled via dictionaries
- Modular structure with reusable functions
- Clean input handling and error checks
- Easy to expand with features like houses, trading, GUI, save/load



---

## How to Run
- visit https://colab.research.google.com/drive/14U94XnuXYbdzSuSQmo9Pa2_nqGfkQ5Al?usp=sharing to run the code


```
python bharat_bazaar.py
