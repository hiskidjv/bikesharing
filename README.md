# bikesharing

## Overview

### The Goal
After a fun time touring NY by bike, an idea for reproducing a bikesharing business in Des Moines has taken root.  With potential investors lined up, we want to visualize the data to tell a story that will help inspire practical conclusions for profitability.  Additionally, we want to help address usage questions that could arise to help support initial modelling decisions for the upstart.

### The Work
This work will require the use of some great Tableau visualizations.  We'll build basic tables, line graphs, heat maps, and more as we find ways to show what might really mattter to our investors.  Two visualizations- the very simple count of rides and the age of riders come from our module work and help show basic usage.  The other five, folded into dashboards (one with headmaps of daily/hourly info, and the other with duration by gender compared to total) are included in our story as well to put it all together.

## Results

### Overview
The seven visualization we have in this challenge help to begin pointing out who is using the ride service in New York, when they are using it, and for how long they tend to use it.  It's a good beginning, but some additional visualizations could certainly help paint a more rounded picture.  Below are some comments about each visualization: [link to dashboard](https://public.tableau.com/app/profile/jacob6486/viz/CitiBikeChallenge_16700194060570/CitiBike?publish=yes "link to dashboard")

### Image by Image
1.  Checkout Times for Users-
This shows us the trip duration (that we first converted into datetime in order to make these visualizations work) broken down by the number of minutes in each of the first three hours.  The graph shows a steep taper down during the first hour, and a low, steady usage of bikes in the second and third hours.  So Citi Bike should be thinking about price points that make sense for those looking for a ride that's about a half hour long in general, with perhaps a price break for those going longer durations (i.e. over an hour).

2.  Checkout Times by Gender-
This shows us that, of the duration results seen in general, it is even more dramatically so for Males, than Females, with a lower and more gradual line for "Unknown".  This might get executives thinking about how to market the service to men as a quick on-and-off service moreso than to women.  Overall, the whole service looks almost 4 times as likely to be used by males than females.

3.  Trips by Weekday per Hour-
This heat map is a helpful image to imediately draw attention to the times (hours) during the week when the bikes are most likely to be used.  It shows two distinct "rushes" - one around 8am and another from 5-7pm.  These are steady results throughout the work week, with the exception of Wednesday.  Weekends tend to die down in general.

4.  Trips by Gender (Weekday per Hour)-
Building on the general heat map of rush times, this shows how it breaks down across genders.  The overall usage patterns are pretty consistent (same heavier times within each gender catergory as within the overall stats).  As seen in the checkout times, male usage is much heavier than any other gender, with a much darker shaded heat map than any other gender.

5.  Trips by User/Gender/Weekday-
I changed the name of this heat map in order to fit it better in the overall dashboard with the last two the way I wanted.  It takes the previous heat maps and further divides it by either general customer or bike sharing subscriber.  This helps show that is was the subscribers that are mostly using the bikes- a fact that should definitely be strongly considered when building in Des Moines.

6.  Number of Trips-
This was the very first visualization of the module, and the most basic "bottom line" number to start the investment discussion.  Is this type of service viable as business?  Start with the 2 million rides counted in New York to rest assured.  I make the font as large as possible so that it would take up more of the story screen when displayed in the presentation.

7.  Rides by Age-
For this line graph, I started with the By Birth Year graph done in the module.  I created a calculated field to make it show the age of the rider in 2019 by just doing (2019-[Birth Year]).  Then I also had to reverse the sort order so the older are on left and younger on right.  This graphs show a clear swell of users between 25 and 35 years of age.  It also has a strange anomaly at 50 yr olds.

## Summary

### What We See
In the story that is created, we show that the service is very popular (in NY at least), that it's typically used for under an hour, that it's most popular as a weekday rush hour service, and that it is generally used by 20-30 year-olds.  This definitely gives the marketting department something to whet their appetites.

### What We Don't See
In the Trips by User/Gender/Weekday heat map, we get the general impression that the bikesharing subscription use is much more popular than the general sales.  But it also grouped outputs by the day of the week only (there were already too many variable being broken out to go further here).  It would help to dive deeper here with two further images put into one more dashboard and one more story item:

1.  Checkout Times by User (which could also be a third part of the Duration dashboard alongside overall and gender breakdowns).

2.  Trips by User (Weekday per Hour) (which could also be a fourth part of the Rush Hour dashboard alongside overall, gender, and users).
