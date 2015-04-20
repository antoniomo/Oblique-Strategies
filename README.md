Oblique Strategies: Prompts for Programmers
-------------------------------------------

Taken from http://kevinlawler.com/prompts:

> Oblique Strategies: Prompts for Programmers
>
> 2015.04.13
>
> Brian Eno created a collection of strategies to help artists break creative
> block. We can do something similar for programmers. Eno's strategies were
> designed to be drawn at random. The strategies here can be drawn at random,
> perhaps via shell script, but have a sort order, to make them easier to read.

Instead of that, I'm putting up a `fortune` file here with all the strategies.
You can simply use `fortune strategies` to get a random one, put this call in a
shell script if you want, or copy/link `strategies.dat` to your system's fortune
data folder.

Add new strategies to `strategies` with a `%` separator, then call `strfile -c %
strategies strategies.dat` to rebuild the updated strategies list.
