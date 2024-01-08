# Using My Cycling Data to Predict Power Output!  

### Problem Statement

Many endurance atheletes know what it feels like to hit the wall or to "bonk". Often times, "bonking" occurs when you burn more energy then you consume- leaving you at caloric deficit during a training ride, race, or any endurance activity. Bonking is something many people hate but experience way too often...

To mitigate bonking, you have to be on top of your caloric intake during your activity. For me specifically, when I'm cycling, I want to know how many calories I need to consume to prevent being at such a high deficit. 

Because of this, I wanted to create a cheeky little tool that can predict how many calories I burn for a given activity based on certain aspects of that activity. One approach is to use my personal cycling data with labeled energy outputs and features. I will explore my data and use it to train an ML model that can predict the energy burned in kilojoues. Based on the amount of energy burned, I can convert this number into calories which should then give me a a good estimate on how many calories I should be eating during a particular ride. 

Data was extracted using my own personal Strava Data. The python script that requests the data, transforms it, and exports it into a csv file can be found here: https://github.com/jairus-m/StravaETLPipeline.

In addition, my full, up-to-date Strava Activity Dashboard can be found here: https://public.tableau.com/app/profile/jairusmartinez/viz/PersonalStravaActivityData/Dashboard1

This dashboard is automatically updated.
