# Wordle-Experiment
Jupyter Notebooks:
-	Wordle_Analysis.ipynb – reads in data, preps data for analysis
-	Wordle_experiment_the_story.ipynb – analysis and summarize findings.
-	World_experiment_the_story.html

## Data files:
-	wordle_experiment.xlsx – tracks daily scores of two players for 40 days
-	There were 4 rounds of 10 days each
-	Each round had a different theme:
  -    Round 1 – players chose their own starting word, but used that same word all round
  -    Round 2 – players started each day with a different word
  -    Round 3 – players both started with ADIEU
  -    Round 4 – players both started with STERN
-	‘nyt wordle good words.txt’ – list of 2308 words retrieved from the New York Times wordle site. These words were visible in the code behind.
	WordleExperiment2022.csv – final file for analysis
##	Data dictionary
-	Date – day of wordle play
-	Round – round of play (1 to 4)
-	Attempt – within round (1 to 10)
-	Score – wordle guess count – score of 7 given with no correct guess
-	Player – player name
-	Word – wordle of the day
-	Guess – starting guess word
-	Difficulty – calculated difficulty based on Words With Friends letter value
-	Type – calculated difficulty category
-	wordsRemain – the number of possible words to guess based on the starting letters. The lower the value, the better the starting guess for the wordle of the day.
