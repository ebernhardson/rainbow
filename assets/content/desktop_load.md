Desktop result load times
=======

When a user types in a search query, it's sent off to the servers which identify and rank probable articles and then return them in a list. In an ideal world this would be instantaneous, but realistically, even with all the caching in the world it's going to take *some* time.

One of the things we anonymously track is how long it takes search results to be provided to the user, after they've sent the request. Here we're displaying the mean, or average, the median, the 95th percentile and the 99th percentile. A caveat when interpreting the results is that the mean may sometimes be *higher* than the 99th percentile, in the case that that last percentile consists of requests that take a truly ludicrously long time to display. *Caveat emptor*.

General trends
------

Load times for results are remarkably consistent, absent the situation, mentioned above, where a tiny number of users face a really slow service. Other than that, there's little interesting to see here unless we decide to start focusing specifically on speeding up the service.

Outages and inaccuracies
------
There are occasionally going to be outages that will affect the accuracy of data. To make it easier to rely on the data (or not!) they will be listed here, from most- to least-recent.

* Between 5 May and 6 May 2015, approximately 40% of incoming EventLogging data was lost due to a wider EventLogging outage. You can read more about the outage [here](https://wikitech.wikimedia.org/wiki/Incident_documentation/20150506-EventLogging).
