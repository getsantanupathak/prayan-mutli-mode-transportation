# prayan-mutli-mode-transportation

### Prayan is an intelligent multi-mode transport platform, for your personal transport network. The platform helps the public and the government to establish an intelligent transport eco-system and continue improving itself by truly using the power of technology. 

The platform uses Machine Learning & Artificial Intelligence on trip information, real-time traffic information to provide features like when to leave for office on day of the week, intelligent routes to save energy for EV vehicles. It also provides analytics, on topics like population density by area compared to public transit routes, to the Government, to help establish new routes or optimize existing routes. Thereby a feedback loop across each components of the eco-system is established. Prayanas a platform, helps to integrate all the three components of a transport eco-system. It provides a unique user-experience, and a set of features, which ensures predictability, safety, and affordability, in a trip.

##### The MVP includes 5+ transit modes with different levels of integration. It will cover 28+ government agencies across the country. The platform is expected to bring in the 5 critical features of an efficient transport system, efficiency, safety, predictability, integrability and affordability.

##### The platform follows a serverless architecture and uses Python, REST API services, Google Maps and latest technologies from AWS & Google. The platform has 4 components: a unified data layer, a sync engine, REST API services and User Interfaces. The data layer is basically a data lake to connect data across different transport organizations and aggregate in an unified manner. It also has AI based components to optimize routing and allow users the flexibility to choose with comfort, cost and time.The sync engine is responsible to keep the data layer up-to-date. It has sub-components that updates pricing information, provides real-time traffic and outage alerts. The next layer is REST API. It ensures accurate integration of different systems and sources. It is responsible to provide one click payment experience for multiple modes in a trip. It allows to have personalized user experience like saving trips, managing custom locations like home, office. It also gives the ability to support local languages in route information. The last layer is for user interfaces. This primarily gives client side features like panic alert generation and custom trip scheduling. 


![Prayan - Platform Design](https://github.com/getsantanupathak/prayan-mutli-mode-transportation/blob/master/prayan_design.jpeg)


### DEMO VIDEO : https://youtu.be/EuMTsCguAms
### DEMO : https://d2lnn9wg7vaqfz.cloudfront.net/index.html 


## Backend Components:
- [Best-Time_To_Travel](https://github.com/getsantanupathak/prayan-mutli-mode-transportation/tree/master/backend_components/Best-Time_To_Travel) : Helps commuter understand which day or the week and what time is the best time to travel to save location like home/work as per his choce. 
- [Electric-Vehicle-Route-Planning-on-Google-Map-Reinforcement-Learning](https://github.com/getsantanupathak/prayan-mutli-mode-transportation/tree/master/backend_components/Electric-Vehicle-Route-Planning-on-Google-Map-Reinforcement-Learning) : Google DeepMind's DQN implementaion aiming to take battery, motor, traffic time, and other factor into account for generating better route (minimize the energy consumption) for the vehicle under certain condition.
- [Traffic-Condition-Recognition-Using-The-K-Means-Clustering-Method](https://github.com/getsantanupathak/prayan-mutli-mode-transportation/tree/master/backend_components/Traffic-Condition-Recognition-Using-The-K-Means-Clustering-Method) : Modified K-means Clustering (MKC) approach to understand Traffic flow modelling and driving condition analysis. 
- [Traffic-Time-Lapse-viewer](https://github.com/getsantanupathak/prayan-mutli-mode-transportation/tree/master/backend_components/Traffic-Time-Lapse-viewer) : A script that makes creating time lapses of traffic in Google Maps easy.
