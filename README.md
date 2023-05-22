# Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants
#programming #datascientist #technology #coding #datavisualization #computerscience #pythonprogramming #analytics #tech #dataanalysis #programmer #statistics #developer #ml #business #zomatodata #innovation #coder #dataanalyst #zomato

def handlerate(value):
    if(value=='NEW' or value=='-'):
        return np.nan
    else:
        value = str(value).split('/')
        value = value[0]
        return float(value)
    
df['rate'] = df['rate'].apply(handlerate)
df['rate'].head()

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, establishment of different types of restaurant at different places, Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry has'nt been saturated yet and the demand is increasing day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. These kind of analysis can be done using the data, by studying different factors.


![__results___63_1](https://github.com/HOSHANGI/Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants/assets/118753140/fe3fc0af-77c2-4ba0-9080-5de9442ac680)
![__results___58_1](https://github.com/HOSHANGI/Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants/assets/118753140/3ea83eb7-98d3-4543-a6af-9e508bbf9a13)
![__results___56_1](https://github.com/HOSHANGI/Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants/assets/118753140/4a2c4f69-832c-46be-bfd8-6570b9390169)
![__results___53_1](https://github.com/HOSHANGI/Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants/assets/118753140/898abf78-2888-4dc7-a9b7-4459146c8eba)
![__results___47_1](https://github.com/HOSHANGI/Data-analysis-and-Visualization-on-Zomato-Bangalore-Restaurants/assets/118753140/e46a7feb-d81d-4d1f-8f67-9b73408ab4ba)
