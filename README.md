# MLB-NHL-result-search-by-team-date
The program prompts the user:
<li>Which Sport? Baseball/Hockey</li>
<li>What Team?</li>
<li>What Year?</li>
<li>What Month? (format 01-12)</li>
<li>What Day? (01-31)</li> <br>

Given this information, we use beuatiful soup and splinter to scrape the results for that sport and day from either Hockey-reference.com or Baseball-reference.com.
The results are put into a dataframe by winning and losing team and associated goals scored for each. 
We then take the user input for "What team?" and attempt to match it with the winners for that date. If there are no matches, it will try to match with the losers, if there are still no matches, a message will display that the team did not play that day.

 <br>
Examples: 

<p align="center"

![alttext](https://github.com/sd2wiebe/MLB-NHL-result-search-by-team-date/blob/main/prog_ex.png)

</p>

<p align="center"

![alttext](https://github.com/sd2wiebe/MLB-NHL-result-search-by-team-date/blob/main/prog_ex2.png)

</p>

<p align="center"

![alttext](https://github.com/sd2wiebe/MLB-NHL-result-search-by-team-date/blob/main/prog_ex3.png)

</p>

<p align="center"

![alttext](https://github.com/sd2wiebe/MLB-NHL-result-search-by-team-date/blob/main/prog_ex4.png)

</p>

<p align="center"

![alttext](https://github.com/sd2wiebe/MLB-NHL-result-search-by-team-date/blob/main/prog_ex5.png)

</p>
