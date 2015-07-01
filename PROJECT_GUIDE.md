1. Download turnstile data for month of May 2015 from http://web.mta.info/developers/turnstile.html.
2. Merge turnstile data into a single file called "turnstile_0515.txt".
3. Check how many unique subway stations in "turnstile_0515.txt".
4. Clean and transform data to include only columns that we need: Station, Date, Time, Entries, Exits.
5. Get top 10 busiest (with most traffic) stations in terms of average entries and exits for May 2015. Create separate analysis for entries and exits.
6. From #5 results, break down counts to the 3 4-hour time intervals: 8am-12nn, 12nn-4pm, 4pm-8pm. Create separate analysis for entries and exits.
7. Plot #5 results using bar graphs. We will have 2 bar graphs. (matplotlib.py)
8. Plot #6 results using line graphs with 3 lines, each line representing time interval. We will have 2 line graphs. (matplotlib.py)
9. Optional: If we can figure out or research about which stations are considered tourist-heavy stations, we can choose to eliminate them from the top 10 list.

Nidhin's "crazy" idea --> according to him!
Show a map of companies within 0.5mi or 1mi radius of each of the top 10 subway stations. Subway stations will have black dots. Companies will be color coded by station they are nearest to.