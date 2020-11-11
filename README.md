## Mystery Word

This is a mystery word game with some personality.  There are both traditional and sinister versions of mystery word selectable from within the game.  The sinister version uses an evil algorithm that never actually chooses a word until it must.  Included in the repo is an annotated demonstration of that algorithm called word-sifter-demo.py

The evil mystery word concept is set out in [this Nifty assignment](http://nifty.stanford.edu/2011/schwarz-evil-hangman/).  

### Requirements
There is no environment required for this other than an installation of python 3.  If running on Windows, one may need to comment out or alter the lines relating to the clear lambda.  They are there to give a cleaner terminal experience, but are currently written for a Mac.  

### Warning

Python 2 will give NameErrors on input, as input() has a slightly different function there.  Please do use Python 3.

## Of Special Note

Please check out the word_sifter_demo.py file.  It demonstrates interactively the way that the word sifter behaves for the evil version.  I have included a very small library of words against which you can make guesses.  The demo then presents you with a full printout on how words are filtered so as to keep the word pool as large as possible so as to keep the narrowing of the field as difficult as possible.
