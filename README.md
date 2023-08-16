# Spotify-streaming-history-analysis
A simple project made on Power BI Report Builder that analyses my Spotify streaming history form January to July 2023. It's almost like Spotify Wrapped, but in the shape of graphs and matrices. 

PBI Report Builder is a data visualisation tool similar to Power BI that offers a convenient platform for creating paginated reports.

To get started, you can request your personal data from Spotify here: https://www.spotify.com/us/account/privacy/

Spotify provides several JSON files containing a variety of information about your account. This project focuses mainly on the streaming history files and the inferences file—the latter containing Spotify's insights into your consumer behavior.

**Cleaning the data:**

First, I used an online tool to convert the JSON files into Excel workbooks.  Using the GetData feature available in Excel, I created another workbook containing a list of the artists and songs I'd engaged with arranged in descending order based on the total streaming time. To further refine the data, I eliminated the datapoints where the "msPlayed" value was less than 30,000 i.e. instances when I'd skipped the song within half a minute.

**I visualised this clean data in the shape of:**
1. Tables of my top ten artists as well as top ten songs with databars to show the number of hours streamed.
2. A scatter plot of the variations in daily engagment representing the number of songs streamed daily.
3. A line chart of the variability in artists and songs displaying the number of unique artists and songs streamed each month.
4. An area chart representing my mothly listenership patterns. 
5. A column chart of the origin of Spotify's inferences about me. 

And that's how I transformed my Spotify streaming history into a symphony of data, notes, and insights!
