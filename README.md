Summary – This is a visualization to show the data between right, left and both handed baseball players.  The baseball players’ performances are explored by plotting with their number of home run and average battling percentage.  Blue circles represent left handed players, red circles represent right handed players, and orange circles represent both handed players.  We can see a correlation between the average battling percentage and number of home run for the players.

Design – The data included height and weight, but I did not include them on the graphs as I do not see a story that correlates with the performance, and they might actually act as a distraction.  I want to design a visual that is simple and straight to the takeaway.  Moreover, I want the audiences to have interaction by clicking on the legend to explore the data for each of the handed dataset.  Lastly, I also want the audiences to be able to interact by drilling down on the players’ name and their performance data by pointing on top of the circles.  I picked scatterplot because it is easy to compare the performance differences for each handedness type in different colors and enable the audiences to see the actual performance numbers (battling avg % and home run counts) for each baseball players.  I designed the circle to have small radius and low opacity to prevent overfilling.  However, the circle size and opacity changes when the user clicks into the legend to view the data handedness individually.

I posted my first draft in the class forum, but I have not received feedback yet.  However, I did share the visual with my wife, colleague, and sister.  After receiving feedback from them, I made several minor changes.  First, I added a descriptive line at the top of the page to explain the main takeaway of the data visual.  Second, I added the measurement unit (%) to my x-axis so the audience can know the battling average is a percentage.  Third, I changed the title to blue color based because my audiences prefer the color blue rather than grey.  Lastly, I added a link to access my Git repository where audience can access my code and the actual data.

After receiving feedback from the grader, I made a few design changes on my data visual.  First, I made the circles smaller to size 2, and started my x-axis from .20 to prevent over plotting.  This will remove a few outliers with battling average lower than .2.  I think this is fine because those players with lower than .2 batting average are mostly pitchers that do not bat much to influence the story of our data.  Second, I did some data exploratory in R and added two boxplots to my data visual.  The first one is a boxplot distribution of handedness in battling average percentage, and the second one is a boxplot distribution of handedness in the number of home runs.   From the boxplot, we can see right handedness baseball players have a lower mean of battling average percentage and a lower home run count.  On the other hand, left handedness baseball players have higher lower mean of battling average percentage and higher home run count.  There is a theory that a batter hits better when the pitcher is different handedness than the batter because there are more right handedness pitchers so left handedness batters are better overall.  However, the chart disproves that theory because both handedness players have lesser battling average percentage than left handedness players.


Feedback – 
I posted my visual on class forum on the link below, but I did not receive a feedback from the class yet.
https://discussions.udacity.com/t/required-project-feedback-baseball-player-data/34992

First feedback I received from my wife:

•	What do you notice in the visualization?
I notice the different color representing for each handedness.  I can drill down on the names to see who the outliners are.
•	What questions do you have about the data?
1)	What is the main take away of this graph?
2)	What is the battling average mean?
•	What relationships do you notice?
The higher the battling average, the more likely the players will have a high count of home runs.
•	What do you think is the main takeaway from this visualization?
There are more right handed players, and the least both handed players.
•	Is there something you don’t understand in the graphic?
Is there any other variables that can affect a player’s performance?

Second feedback I received from my colleague:

•	What do you notice in the visualization?
I like the legend and how the user can interact with the data if they want to explore it.
•	What questions do you have about the data?
1)	Why is the title colored grey?   It is hard to see.
2)	What is the purpose of the visual?								
•	What relationships do you notice?
The best players are either right handed or left handed.
•	What do you think is the main takeaway from this visualization?
It is better to practice with one hand and to master it than to practice with both hands.
•	Is there something you don’t understand in the graphic?
No.

Third feedback I received from my sister:

•	What do you notice in the visualization?
The data is not linear.  The better the battling average, the more home runs the players can get.
•	What questions do you have about the data?
1)	Where can I get the code and the raw data?
2)	What is the measurement unit for the battling average?
•	What relationships do you notice?
Players from different handedness have similar trend on their performance data.
•	What do you think is the main takeaway from this visualization?
There are a few outliers on the data.  Practicing with both hands to adjust to the pitcher will not result in a higher performance.
•	Is there something you don’t understand in the graphic?
No.

Resources – I used this advanced example template from dimplejs.org and Udacity class examples in lesson 2 to design my data visual. 
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
https://www.udacity.com/course/viewer#!/c-ud507-nd/l-3168988586/e-3063989008/m-3063989009

