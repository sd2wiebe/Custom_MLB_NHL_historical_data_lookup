# MLB-NHL-result-search-by-team-date
The program prompts the user:
<li>Which Sport? Baseball/Hockey</li>
<li>What Team?</li>
<li>What Year?</li>
<li>What Month? (format 01-12)</li>
<li>What Day? (01-31)</li>

Given this information, we use beuatiful soup and splinter to scrape the results for that sport and day from either Hockey-reference.com or Baseball-reference.com.
The results are put into a dataframe by winning and losing team and associated goals scored for each. 
We then take the user input for "What team?" and attempt to match it with the winners for tht date, and if no matches, then try with the losers, and if still no matches, a message displays that the input team did not play that day.
If we construct a message with the date the score and which team beat which.
ex:
