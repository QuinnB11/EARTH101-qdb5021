# What Does This Tool Do?

### Pulling from an API  
This tool pulls from an API hosted by USGS, a United States Government agency that tracks natural disasters. It specifically follows the coordinates (longitude and latitudinal) around the Middle East, a hub for earthquake activity. It then pulls all earthquakes above a magnitude of 3 from the past 365 days (1 year) in a 1500 km radius around Turkey. 

### Creating our Dataset  
Once we have called the API, we create a dataset that uses longitude and latitude received from the API to categorize different earthquakes. The full data on each earthquake includes location, magnitude, time, latitude, longitude, and the weight (number of earthquakes in that location with an average in magnitude).

### Understanding the Data  
We can then create a heatmap based on the location of each earthquake as well as create different tables that allow one to visualize the number of earthquakes, as well as compare different locations to determine high-risk areas. This allows for a very deep understanding of the level of danger to earthquakes different cities have. The hope for this project is to continue to use some AI model that will use previous data to better predict future occurrences. This dataset goes further back than 1 year, and I hope that I will be able to create better tables and graphs that depict the world of earthquakes in more depth.

# Future of Earthquakes

### Location  
The Middle East is one of the most prominent locations of earthquakes in the modern era as they have torn apart many different communities. The data shown does not indicate the frequency of earthquakes increasing, but the scale of their devastation is. Dr. Brian Baptie, a seismologist with the British Geological Survey, says that this is because the global population is increasing, with many living in densely populated areas (built-up). That includes areas such as Turkey in the Middle East and regions in India and Pakistan [2]. To note, the belt that we are specifically documenting with this tool is the Alpide earthquake belt, which travels through the Middle East and down towards the Indonesian region [2].

### Human Causes  
While contrary to popular perception, climate change is not a factor in earthquakes, human activities such as mining, reservoir-induced seismicity, or oil-and-gas extraction can contribute to seismic events in the Middle East according to Van Der Lee, a professor in Earth and Planetary Sciences at Northwestern University, US [2]. This phenomenon was documented in our class and can be seen throughout history among many different oil drilling operations. Another thing to note that specifically affects the Middle East is groundwater extraction. It has been observed to be linked to earthquakes in some parts of the Middle East – for instance, along the Dead Sea Fault in Jordan at the Wadi Al-Arab basin [2].

### AI to prevent Earthquakes  
Advancements in AI have revolutionized fields from medicine to finance, enabling unprecedented insights through data analysis and predictive modeling. Its capacity to process vast amounts of information has propelled human understanding by uncovering patterns and correlations previously unseen. This innovation has recently been turned towards natural disasters as an AI algorithm developed by researchers at The University of Texas at Austin correctly predicted 70% of earthquakes a week before they happened during a seven-month trial in China [1]. Specifically, the AI was trained to detect statistical bumps in real-time seismic data that had been paired with previous earthquakes. The outcome was a weekly forecast in which the AI successfully predicted 14 earthquakes within about 200 miles of where it estimated they would happen and at almost exactly the calculated strength. It missed one earthquake and gave eight false warnings [1]. This is a huge development as it can make many different methods of protection for people possible. Evacuations would be simplistic, as a week notice is surely enough time to evacuate even the most densely populated regions of the world.

# Work Cited  
[1] “AI-driven earthquake forecasting shows promise in trials,” PreventionWeb, https://www.preventionweb.net/news/ai-driven-earthquake-forecasting-shows-promise-trials (accessed Apr. 24, 2024).  
[2] J. Bell, Seismic threats: Are earthquakes becoming more common ..., https://english.alarabiya.net/News/middle-east/2024/01/26/Are-earthquake-related-disasters-becoming-more-common-and-deadly-in-the-Middle-East- (accessed Apr. 24, 2024).

# Github Link  
Attached below is the entire GitHub link to my repository. There you can run the Jupyter notebook yourself (given the prerequisites of Python and the required libraries).  

https://github.com/QuinnB11/EARTH101-qdb5021

### Author: Quinn Butcher
