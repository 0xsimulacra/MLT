# Machine learning on ATP and WTA Tennis Matches with Betting odds Data


###### Dataset can be found on Kaggle on : https://www.kaggle.com/hakeem/atp-and-wta-tennis-data

###### Work done on the data wich is EDA, Data prepartion, modeling, predictions then Betting based on diferents stategies on ATP data can too be found on Kaggle on : https://www.kaggle.com/hakeem/eda-data-prep-modeling-predictions-then-betting

### Context

ATP and WTA matches results and betting odds from year 2000 untill 2019.

Results for the men's ATP tour date back to January 2000, including Grand Slams, Masters Series, Masters Cup and International Series competitions. Historical head-to-head betting odds go back to 2001. And from 2007 results and historical betting odds for the women's WTA tour as well!

### Content


Description of data:

-  Results Data:

ATP = Tournament number (men)

WTA = Tournament number (women)

Location = Venue of tournament

Tournament = Name of tounament (including sponsor if relevant)

Date = Date of match (note: prior to 2003 the date shown for all matches played in a single tournament is the start date)

Series = Name of ATP tennis series (Grand Slam, Masters, International or International Gold)

Tier = Tier (tournament ranking) of WTA tennis series.
Court = Type of court (outdoors or indoors)

Surface = Type of surface (clay, hard, carpet or grass)

Round = Round of match

Best of = Maximum number of sets playable in match

Winner = Match winner

Loser = Match loser

WRank = ATP Entry ranking of the match winner as of the start of the tournament

LRank = ATP Entry ranking of the match loser as of the start of the tournament

WPts = ATP Entry points of the match winner as of the start of the tournament

LPts = ATP Entry points of the match loser as of the start of the tournament

W1 = Number of games won in 1st set by match winner

L1 = Number of games won in 1st set by match loser

W2 = Number of games won in 2nd set by match winner

L2 = Number of games won in 2nd set by match loser

W3 = Number of games won in 3rd set by match winner

L3 = Number of games won in 3rd set by match loser

W4 = Number of games won in 4th set by match winner

L4 = Number of games won in 4th set by match loser

W5 = Number of games won in 5th set by match winner

L5 = Number of games won in 5th set by match loser

Wsets = Number of sets won by match winner

Lsets = Number of sets won by match loser

Comment = Comment on the match (Completed, won through retirement of loser, or via Walkover)

- Betting odds data:

B365W = Bet365 odds of match winner

B365L = Bet365 odds of match loser

B&WW = Bet&Win odds of match winner

B&WL = Bet&Win odds of match loser

CBW = Centrebet odds of match winner

CBL = Centrebet odds of match loser

EXW = Expekt odds of match winner

EXL = Expekt odds of match loser

LBW = Ladbrokes odds of match winner

LBL = Ladbrokes odds of match loser

GBW = Gamebookers odds of match winner

GBL = Gamebookers odds of match loser

IWW = Interwetten odds of match winner

IWL = Interwetten odds of match loser

PSW = Pinnacles Sports odds of match winner

PSL = Pinnacles Sports odds of match loser

SBW = Sportingbet odds of match winner

SBL = Sportingbet odds of match loser

SJW = Stan James odds of match winner

SJL = Stan James odds of match loser

UBW = Unibet odds of match winner

UBL = Unibet odds of match loser

MaxW= Maximum odds of match winner (as shown by Oddsportal.com)

MaxL= Maximum odds of match loser (as shown by Oddsportal.com)

AvgW= Average odds of match winner (as shown by Oddsportal.com)

AvgL= Average odds of match loser (as shown by Oddsportal.com)

### Acknowledgements

The Data is scraped from http://www.tennis-data.co.uk.

In their website they wrote : 

All files are available in CSV/Excel format for PC Windows operating systems, and are updated weekly at the end of each tournament (2 weeks after Grand Slams). CSV format is the industry standard comma delimited file format allowing compatibility with many computer spreadsheet applications. Commas are used to separate columns of data. They will only be seen if a CSV file is opened in a text editor. Tennis-Data's preferred spreadsheet application is Microsoft Excel, offering a full range of analytical functions to test betting systems developed from match and odds data.

Tennis-Data would like to acknowledge the following sources which are currently utilised in the compilation of Tennis-Data's results and odds files.

Results:
Xscores - http://www.xscores.com/
ATPtennis.com - http://www.atptennis.com/
ATP Tour Rankings and Results Page - http://www.stevegtennis.com/
Livescore - http://www.livescore.net/

Rankings:
ATPtennis.com - http://www.atptennis.com/
ATP Tour Rankings and Results Page - http://www.stevegtennis.com/
WTA TOur Rankings - http://www.sonyericssonwtatour.com

Betting odds for matches generally represent the most recent before play starts, as reported by oddsportal.com and the individual bookmakers.


### Inspiration

Can we perdicted the outcome of the matches for one year based on the data from prior years ? Can we have a good return on investement using a beting strategy based on those predictions ?

### Work done:

EDA, Data prepartion, modeling, predictions then Betting based on diferents stategies on ATP data ===> Notebook named ML-on-ATP
