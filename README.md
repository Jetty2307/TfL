# TfL
London Underground crowding analysis project

Description: 

London Underground is one of the largest underground systems in Europe and in Top 10 in the world by number of stations. Currently, the number of stations amounts to 272, located on 11 lines. The annual ridership in the Underground exceeds 1 billion people. That creates a large burden onto the system, especially during the rush hours and big events in the city. It is also important to note that the Tube is the oldest metro system in the world, and many stations were constructed at the time when such huge ridership could not have been expected, so those stations don’t have too much space to cope with relevant passenger flows, and the reconstruction of such old stations doesn’t seem feasible. Moreover, most of those stations are situated in the city centre and/or are interchange stations, which stimulates crowding. Regular construction works and occasional breaks in the Underground create additional potential for crowding. The crowding at the station in its turn may delay the loading and departure of the trains which initiates the vicious circle leading to further crowding on that station and consequent stations along the line. That may result in loss of reliability and eventually profitability of the system. This is also a potentially dangerous situation which can lead to accidents at the station. 

Goal: 

The best way to handle crowding is to have precise knowledge and a robust prediction solution for crowding expected in few hours/days on each station. This can give the system staff an opportunity to react promptly on coming crowding events. For instance, the headway can be decreased during that time on respective lines, or additional personnel can be deployed at the station to smooth the process of entering/exiting the train/platform and preventing the accidents. The passengers may also be informed about upcoming congestions by means of visual or sound announcements, as well as in mobile apps. 

Comprehensive visualization of crowding-related data may help with identifying strategic problems and bottlenecks in the system alleviating further decisions on renovation and development of the system. Again, this information might be also useful for frequent Tube users while planning their routes. 

Technical solution: 

The project consists of two parts: visualisation of most characteristic data related to crowding at the London Underground stations and construction of the predictive model for future expected crowding at the stations during the specific 30-minute time frame on a particular day. For both parts, the data from Transport for London (TfL) Unified API are used. Information on crowding is available upon API requests as processed historical data (crowding at each station on a specific day of the week in a specific 15-minute time interval), or as live data (current crowding at the specific station). 

Visualization: historical and live data for London Underground with various types of plots, including visualization on a geographical map. Tools: Jupyter, Tableau dashboards.
Predictive model: time series model (ARIMA), gradient boosting (xgboost) in Python, Tableau dashboards to evaluate the quality of the models by comparing predicted and actual data.
