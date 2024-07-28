**Messaging**: This visualization project uses the 'Population of All US Cities 2024' dataset, which provides information about the population of 300 popular U.S. cities in the years 2020 and 2024. The data is visualized to show the geographical information of each city and how the population changes over four years. By providing overviews of population changes and population information for each city, this narrative visualization can be useful for selecting work locations, academic purposes, or other uses. This description is also shown as the introduction of the dataset on the narrative visualization website.

**Narrative Structure**: This narrative visualization follows an interactive slideshow format. There are three slides in total: 'Area vs Population in 2020' (default view), 'Area vs Population in 2024', and 'City Population Trends' (annual population change in each city between 2020 and 2024). These graphs provide overviews of population changes and population information for each city. The three scenes highlight different data columns and details within the same dataset. Viewers can transition between different scenes by clicking the buttons with chart or slide title names on them (the names are specified above).

**Visual Structure**: Right below the scene selection buttons, there are different introductions for the selected slides, which help viewers understand the data. Besides, there are select buttons for census regions, allowing users to drill down into more information by clicking each button, and the chart will filter out the data and only keep the data specified by the selected button. Users can look for detailed highlights for each census region, such as Western, Midwestern, Southern, and Eastern States, as well as more specific regions like the Pacific States or South Atlantic States, by simply mousing over the legends beside the graph (this interaction will be triggered by hovering/un-hovering the legend of the region). There are different color schemes and different charts used in different scenes, and there are automatic pop-up annotations for noteworthy data. Viewers can also click each data point or bar in the charts to see more details, which urges them to focus on the important parts as well as the parts they want to explore. All the data points and axes for charts are well labeled. Each scene is a slide, and each slide contains a chart, with descriptions and drill-down details. Therefore, it remains user-oriented and clear. On different pages, there are not only annotations highlighting important points from the data directly but also tooltips for the current data points. Also, The reference and author information are listed at the end of each scene.

**Scenes**: Moving from slide to slide, users can first observe population information for 2020 for each city, then similar information for 2024 in the next slide. The first two scenes are ordered by timeline. Lastly, in the third slide, users can find information about annual changes in these cities from 2020 to 2024. This scene is the last because it is the comparison between different times.

**Annotations**: The annotations in this narrative visualization are simple. As specified above, there are annotations shown for the details of cities with maximum and minimum population density. Scenes one and two have different annotations because the targeted cities might be different, and the annotations will be cleared and redrawn when the user selects different census regions (annotations will then show the details for those cities within the selected regions) and different scenes. Whenever viewers click different data points, a window will pop up with details of the data points. In general, annotations and pop-up information will change within a scene and between scenes.

**Parameters**: Parameters include three slide numbers that control the scenes. Selected census regions are parameters controlled by the buttons, which help the user select regions. In the third scene, there are parameters controlling how the data should be sorted, giving users different views of the bar charts. Parameters are used on legends; hovering or un-hovering on legends changes the parameter, which lets the charts know which census region the viewer wants to highlight. Clicking on each data point changes the parameters associated with each point, which controls the visibility of the pop-up windows.

**Triggers**: Parameters are mainly controlled by buttons. Clicking on different buttons triggers different parameters to change. For example, scene number changes can trigger changes in the graph descriptions, annotations, and data points within the graphs. Additionally, it changes the parameters controlling the visibility of different buttons. Clicking on buttons for different census regions also triggers other actions, such as changing the visibility of the data points and annotations. After filtering out some data points by census regions, previous annotations change because the city may not be in the selected regions.
