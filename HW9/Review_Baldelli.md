## The remade plot
Remade plot:

![alt text](https://github.com/TJTomas/DSPS_TTomaszewski/blob/main/HW9/Redone_Plot.png "Good Plot")


Original plot:

![alt text](https://github.com/TJTomas/DSPS_TTomaszewski/blob/main/HW9/old_Plot.png "Good Plot")


The inclusion of the horizontal grid axis reduces the ambiguity of the points' location, and the decreased size of the plot also makes it easier to compare across clusters.
I like the labeled x-axis. It makes it very clear this is a discrete group, but I would remove the x-axis label, as this is repeated information.

The new colors are better for colorblind viewers, but the use of colors, the x-axis, and the legend introduces redundancy into the plot. 
Using only the label axis would be better to reduce redundancy and increase the data-to-ink ratio. 

The alpha used to clearly show all points reduces the ambiguity of the original plot. 
To take this a step further, I would reduce the alpha further and make the points smaller as well. 

Overall this iteration of the plot has a much better data/ink ratio, less ambiguity, and is an overall improvement from the original plot.


## The "Bad Plot"
![alt text](https://github.com/TJTomas/DSPS_TTomaszewski/blob/main/HW9/bad_plot.png "Bad Plot")

This plot is a pie chart, which inherently carries a high distortion rate. A bar graph could convey the same information with less distortion.
The labels could be put directly annotated in the pie chart, or in the case of a bar chart, [0, A, B, C] could be used as the x-axis ticks with "Phase" as the label. 
This would improve the data/ink ratio.

In addition, the chart's phases being 0, A, B, and C are inconsistent, and unless there is a good reason, consistency should be maintained.
Labeling that is more illustrative of what is being measured would also improve the ambiguity of this plot. 

The caption suggests this is a time distribution plot, indicating that the data is ordered. 
The circular pie plot does not convey this. 
This plot shows the time spent on each part of a project, which was primarily done sequentially (according to the paper). 
Given this, a Gantt Chart would best convey the data in this plot, or a single horizontal stacked bar chart.

The main issue with this plot is inconsistency and ambiguity, leaving much to be improved.



