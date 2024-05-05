# Geography Game
CLI-based geography game made in Python using border-based data of the world's countries to allow the user to make a journey from a starting country to a destination country.
## Find the random country!
The game starts by randomly selecting two of the world's countries (that are able to be connected in some fashion) from a database and selecting one as the start and one as the finish. 
The user will then be prompted to input a country bordering the starting country.
Using an algorithm, the program will determine if this guess was the best (or equivalent to the best) possible guess to create a journey using the least amount of countries.
## Outcomes of user guesses
- If the user selects one of the countries that are along the most efficient journey, the program will congratulate them and prompt them to continue guessing countries along their journey.
- If the user correctly guesses a bordering country, but not one that is along the most efficient journey, the game will notify the user of their mistake, but allow them to continue guessing along the journey.
- If the user guesses a country that is not bordering the country that the journey is currently on, the game is over.
## Winning
As previously mentioned, the game will only continue so long as a continuous streak of countries is guessed from the starting country to the destination country.
In the event that the user is able to do this, the game will congratulate them on their victory and display the most efficient journey possible.
If the user manages to create the "best-possible" journey of the smallest number of countries used, the program will give a special congratulations to the user for their perfect game.
If there were multiple "best-possible" journies, the program will display the first one found by the algorithm as an example but still recognize a journey of equal length to the "best-possible" journey as a "perfect game" 
