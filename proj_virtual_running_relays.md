**Virtual Running Relays**

By Tamela Maciel, May 2020

ABOUT:

*West End Runners in Leicester challenge local clubs to a virtual running relay*

During the lock-down, club runners are missing the buzz and companionship of races. But we can still compete virtually!

35 runners per club, 30 minute slots run from anywhere, how far in total can each club go? 
Most cummulative mileage wins.

![alt text](https://raw.githubusercontent.com/tamelamaciel/virtual_running_relays/master/club_jerseys.jpg "West End vs WDAC")

This jupyter notebook digs into the stats of two recent races:  
* 2 May: West End Runners (WER) vs Wigston Phoenix (WP)  
* 9 May: West End Runners (WER) vs Wellingborough & District Athletic Club (WDAC)  

Various statistical plots are created, such as this plot of total mileage difference throughout the day between WER and WDAC:

![alt text](https://raw.githubusercontent.com/tamelamaciel/virtual_running_relays/master/total_mileage_differenceWER_WDAC.png "West End vs WDAC")

And this boxplot showing the variation of individual runner mileage between each club:

![alt text](https://raw.githubusercontent.com/tamelamaciel/virtual_running_relays/master/boxplot_mileage_variationWER_WDAC.png "West End vs WDAC")

Gpxpy and Folium are used to create a heat map of routes, drawn from individual gpx files and coloured by club:

{% raw %}
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0"
width="700" height="500" src="/assets/map_WER_vs_WDAC.html"></iframe>
{% endraw %}

For full window map, [click here](/assets/map_WER_vs_WDAC.html)

For more details and code, see the [GitHub repository](https://github.com/tamelamaciel/virtual_running_relays).
