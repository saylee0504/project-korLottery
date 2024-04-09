[project 1] Korea Lottery Number Recommendation System

Hi~ I am Say~Lee.<br>
I am a beginner data analyst who has just started learning Python. 😀<br>
so plz don't be too hard on me, even if my skills are horrible. 😕<br>
I am planning to make posts of my work on Github from now on, plz enjoy it!<br>

My first project is a lottery number recommendation system for the South Korean Lottery system known as 'Lotto'!<br>

While there are already many lottery number recommendation services available in Korea, <br>
Lotto has been subject to suspicions of manipulation. <br>
There are several reasons for this:<br>

1. The first prize winning numbers have never been repeated in history
2. There has never been a time when no one won the prize.

As someone who buys Lotto every week myself, I become curious about whether there might be real manipulation involved.

So I proposed the following approach:

[First] I formulated a hypothesis.
"Lotto is manipulated
This hypothesis incorporates situations where people have raised concerns about manipulation into the code.

(1) all the historical first prize winning numbers are excluded.
(2) Among the numbers with the least number of winners, at least one will be selected as the winning number.

[Second] To achieve this, I simulated the scenario of the first round of Lotto purchases and conducted experiment by:

(1) Generate random number lists as many times as the average number of Lotto purchases for a week.
(2) Delete historical first prize winning numbers
(3) Select the number lists with the lowest duplicate counts.
(4) Randomly sample 5 sets of numbers from the selected lists. 

As I am just beginning to study programming, the code may be quite messy.
I used too many for loops, which resulted in long execution times.

Please don't be too critical 😥
