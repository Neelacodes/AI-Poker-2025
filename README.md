# AI-Poker-2025
Ace is either high or low (whichever gives best hand). no side pot. one table plays 20 games. round-robin. create a player class that inherits from Player and overrides the function action. This function will receive the game state (structured in the format given below) and the action histories. This function must return a tuple containing the action (PlayerAction) and the amount (0 in case of fold, check).