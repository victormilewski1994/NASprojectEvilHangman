# Evil Hangman
Victor Milewski (victormilewski@gmail.com)  
University of Amsterdam, 10529136  
Class Native App Studio  

This is an android app where a user can play a fun and different version of the classic hangman! In Evil Hangman you are not guessing one word. The app takes all the words from a single length in his memory. After every guess subsets are created from possible letter positions, and the largest subset contains the final word... Mwahahah!

## How to Use
1. Go to releases
2. Download the latest release
3. Unzip the file
4. Load the folder 'EvilHangman with android studio
5. Run the app

##### Warning
When the game type is evil, a powerset is created depending on the wordlength. If the wordlength is chosen to long it might look if the app is broken. Start with smaller lengths and build it up. 

If it takes to long and you don't want to wait, restart the app. If the length was largen then 14, it is reset after one game to a low value. 

## App's Features
Here is a list of features that are in this app:
* The app uses a large wordlist to select words from. This makes it unlikely that you see the same word over and over again.
* Every time you guess a word, your score is increased by one. When you cannot guess a word, your score is placed on the highscore list(if it is in the top 10 scores).
* When you close the app, the game remembers the state. So the score and the guessed letters for this word are remembered. So you don't have to stop your winning game, bacause of lack of time. 
* The user can select in the settinngs what the word length of the words has to be. 
* The user can select to play the classic hangman or the evil hangman.
* The user can select how difficult the game is by changing the number of guesses.  

## Users Experience
When the game user starts the game for the first time, he is immediatly in the game. The title of the game is shown at the top, besides this is an menu with a couple of options: go to settings, go to highscores or start new game.  

In the middle of the screen is an empty space where a gallow will be drawn. By every wrong guess a part of the gallow is added. Below the gallow some bars are shown, to display the length of the word and which letters are guessed. At the start no letters are guessed, but further along in the game the bars get replaced by the letters.  

Below the word, there is place to add a list of guessed letters. After every guess, wrong or correct, the list increased in size. 

![Alt text](/images/GameActivity.png)

When a user decides to play in landscape mode, the layout is changed. At on side of the screen will be the gallow and at the other side will be the word and the list of letters.  

In the highscore screen there is a switch. If it is on, the highscores from evil hangman are shown. If it is of, the highscores of the classic game are shown. 

![Alt text](/images/HighscoreActivity.png)

In the settings screen there are three options. The first option is to change the type of the game, evil or good. This is done with a switch. There are two sliders, one is for the wordlength and the other one is to set the number of guesses. 

![Alt text](/images/SettingsActivity.png)

