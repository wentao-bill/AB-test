# AB Test for Cookie Cats

<p><a href="https://www.facebook.com/cookiecatsgame">Cookie Cats</a> is a hugely popular mobile puzzle game developed by <a href="http://tactile.dk">Tactile Entertainment</a>. 

It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. It also features singing cats. 

Short video demo:</p>
<p><a href="https://youtu.be/GaP5f0jVTWE"><img src="https://assets.datacamp.com/production/project_184/img/cookie_cats_video.jpeg" style="width: 500px"></a></p>

## Setup
<p>As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. 

In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.</p>
<p><img src="https://assets.datacamp.com/production/project_184/img/cc_gates.png" alt></p>

## AB Test
For this AB Test, the gates have been placed at level 30 ***(control)*** and 40 ***(treatment)*** respectively. In this notebook, we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40, and examine the impact on player retention.

## Data
You can find the original dataset on Kaggle [**HERE**](https://www.kaggle.com/arpitdw/cokie-cats)

This notebook is based on the project I completed on Datacamp
