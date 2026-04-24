# **Analysis of New York Airbnb Data**
Exploratory Data Analysis of New York Airbnb Data, visualized using ArcGIS API for Python


**Team Name:** Coraline and A Nun Walk Into A Bar

**Team Members:** Farnaz Mozhgani (fmozh001(862273989)), Ashley Pang (apang024), Yeahn Kim
(ykim384)

**Problem Statement:**

We plan to examine AirBnB data in the New York area during 2019. We want to understand more about
why a person chooses a certain listing (based on location/area, ratings, name, host, and price).
For example, we want to examine certain correlations between the number of reviews and nights guests
stayed and see if a new guest would prefer booking a room that has more reviews or if other factors could
be involved including locations.
Additionally, we want to see if we can find any patterns among locations to find out if certain locations
are preferable and possibly why. And to see what we can learn from hosts and the areas.
We are also interested in using this project as a baseline recommendation for Airbnb customers when it
comes to choosing their Airbnb location and growing this project as we get more data and reviews for
different locations. We are also planning to make visual location maps using specialized libraries with
better views and map it to the dataset features for better visualization and readability.

**Why is this problem important?**

This problem is important because hosts of Airbnb can use this to make their listings more appealing.
AirBnB could use it to create a better recommendation tool or suggestion algorithm. It can also be used to
possibly create a red flag/green flag system to alert future users. Also, future AirBnB hosts can use it to
find better locations to start their business. This project could help travelers not fall into scams and/or use
this tool to make sure they have a safe stay at an Airbnb.

**Works Cited:**

● Mingming Cheng, Xin Jin, What do Airbnb users care about? An analysis of online review comments, International Journal of Hospitality Management (2019)(https://www.sciencedirect.com/science/article/pii/S0278431917307491)

This paper is a study of tourism, what customers prefer during their Airbnb stay, and how
they tend to rate their experience. The contributors have used text mining techniques and
sentiment analysis to analyze the comments made by Airbnb guests. Then this
information is used to see how the guests tend to evaluate their experience and what
major features are considered for a positive experience vs a negative experience.

● Chica-Olmo, J., González-Morales, J. G., & Zafra-Gómez, J. L. (2020) . [Effects of location on
Airbnb apartment pricing in Málaga.](https://www.emerald.com/insight/content/doi/10.1108/tr-10-2020-0476/full/html?skipTracking=true) Tourism Management, 77, 103981.

The authors used readily available information from Airbnb’s online platform and from hotels in
order to understand how the spatial distribution of the listings in London relates to multiple
different factors such as demographics and environment. This paper found that Airbnb and hotels
are usually found around tourist attractions that are popular and usually central to the whole
location studied. They also found Airbnb exceeded hotels in quantity and coverage. The use case
of this information is to suggest locations to place future Airbnbs and suggest how local councils
should regulate Airbnbs. However, the limitation to this research is that it was only done in the
area of London and is based on secondary data.

● Donghun Lee, Woochang Hyun, Jeongwoo Ryu, Woo Jung Lee, Wonjong Rhee, and Bongwon
Suh. 2015. [An Analysis of Social Features Associated with Room Sales of Airbnb](https://dl.acm.org/doi/10.1145/2685553.2699011). In
Proceedings of the 18th ACM Conference Companion on Computer Supported Cooperative Work
& Social Computing (CSCW'15 Companion). Association for Computing Machinery, New York,
NY, USA, 219–222.

The authors looked into AirBnB which is a type of collaborative consumption. They collected
their AirBnB data by crawling on a specific date located at 5 predecided cities in the USA. After
cleaning and preprocessing their data, they analyzed it to find features influencing room sales and
their effectiveness. They found out that features including ‘The Responsiveness of Hosts’, ‘The
Count of Wish List’, and ‘The Number of Reviews’ highly influenced room sales. The result of
this research shows the characteristics of modern collaborative consumption systems and how
they should be designed. However, the data used in this research was not large enough and did not
include some qualitative data.

**Plan Outline:**
1. Turn in the project proposal
2. Gather datasets on Google Collab
3. Separate tasks for data cleaning/integration/transformation
4. Gather our findings, results and make some analysis of the results, and document them.
5. Make any improvements and adjustments as needed.
6. Work on the project presentation, bring our analysis together and outline what we want to present
and what important information we want the audience to know about our project.
7. Practice for the presentation, make some slides and documents to demo in the class, and wrap up
the project.

**Workload Distribution**

● Phase 1: Each team member prepares their dataset and ideas to discuss and decide on the final
project proposal. We will each bring data related to a specific problem statement and combine the
data to be used for the next phase of the project.

● Phase 2: After discussion, we will integrate all the collected data, decide which data cleaning is
needed, and divide the work. Planning on implementing different types of data cleaning and data
transformation algorithms as needed, and assigning each algorithm to a person.

● Phase 3: We will discuss which visualization best represents the data in the sense of AirBnB
recommendation. We want to be able to visualize the results of our findings which can help us
make some conclusions on questions in our problem statement.
For the location and mapping aspect of our project, we need to decide what graphing library and
tool is best for the purpose of this task.
● Phase 4: We divide the presentation into 3 parts and each prepares their designated part to present
and show in the class.

**Dataset chosen for the project:**

● NY-AirBnB: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

**Evaluation Plan:**

● Cluster locations to find popular locations.

● Use the location, ratings, name, host, number of nights, and price to see which is a better
predictor of higher customer renting/reviews.

● We can evaluate the datasets by using some of the non-trained entries and see if it can correctly
predict the number of reviews.

● Using correlation to find any repetitive patterns among the features in the data science and
evaluate to see if it makes sense or not.
