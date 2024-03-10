# Duolingo-Word-List-Extraction
In this short Python code, one can semi manually extract the word list of a Duolingo Course (word, translation and pronounciation audiofile) to an anki deck.
There are browser plug ins, but since Duo changes a lot recently, they dont work atm (10.3.24)

How to use:
Just follow the instructions in the Jupyter Notebook. 
Might have to install BeautifulSoup, gtts via pip
  pip install bs4
  pip install gtts

On the website of duolingo, sign in and go on the word list. For some languages, there is a card deck function, but eg for danish there isnt
Scroll down until all words youve learned are listed
Press Q (view HTML) and copy into a file (here Testfile.txt)

Then start the Code
If you whish to use another language, you have to change that in the pronounciation part

You can update your wordlist whenever you have learned some new words


ANKI:
Import the list, choose comma as separator and if you want both the written word and audio files to play,
choose 3:Audio as front page. English as Back page

If there are any questions or requests, feel free to contact me 
