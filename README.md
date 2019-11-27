# udacity_nd025_term2_project_1
That's my project 1 for Udacity's nanodegree "Data Science - Term 2"

As attendee I had to choose one dataset and do some data science analysis.
I chose some data from the NFL, found at kaggle https://www.kaggle.com/maxhorowitz/nflplaybyplay2015

There is a medium blogpost at https://medium.com/@dfv.ms/will-my-team-get-a-first-down-right-now-c9c2bec61a81 about this analysis.

## Play-by-play data from the NFL

The data contains play-by-play data from the NFL season 2015. So I decided to look at questions like

* Can I predict if a team gets a first down given some data like down, field position, yards to go and time on clock?
* What's the probability to get a first down?
* Is there a dependancy to the team with the ball?

These are typical questions a Head Coach should answer when deciding "going for
it on 4th down" or not.

I can show that you can predict the probality of a first down depending on the
position on the field.

There is also a dependancy regarding the team in possession of the ball.

I'll compare the SuperBowl teams Denver and Carolina with the worst teams of
the 2015 season Tennessee and Cleveland.

## Work on your own

### Long way
If you want to run the analysis you have to clone the Jupyter Notebook onto your computer by

```bash
git clone https://github.com/dfv-ms/udacity_nd025_term2_project_1.git
```

and download the dataset https://www.kaggle.com/maxhorowitz/nflplaybyplay2015#NFLPlaybyPlay2015.csv and put it into the subdirectory "data".

### Fast way
Using the wonderful tool binder: Just click onto the button:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dfv-ms/udacity_nd025_term2_project_1/master)

Download https://www.kaggle.com/maxhorowitz/nflplaybyplay2015#NFLPlaybyPlay2015.csv and upload the file into the data directory.

### Used libraries
Running the python 3.7 code requires the following python packages:
  * NumPy (1.16.2)
  * Pandas (0.24.2)
  * Scikit-Learn (0.20.3)
  * matplotlib (3.0.3)

### Files
* nfl-2015_play_by_play.ipynb The Jupyter Notebook with the analysis.
* README.md This file.
* LICENSE The license used for this project.
* data An empty directory where you to put the data into. Due to the unknown status
of the license of the data I can't redistribute it here.
