# Road to beer experts: how do beer tastes evolve through time?

## Abstract
From our own experience, we can tell that our beer tastes have drastically evolved over the past 10 years. At first, we only drank Pils and found other types of beer difficult to enjoy. Today, we can enjoy an IPA but are not yet satisfied when being served a Guinness. 

An obvious question occurs: are these shifts in beer tastes we experience common to other beer drinkers as well? By analyzing detailed beer ratings submitted by millions of users on two of the largest beer rating websites worldwide, namely [BeerAdvocate](https://www.beeradvocate.com/), we want to determine if and how beer tastes of people evolve through time. To tackle this question, we explore and combine different data representation techniques. Moreover, using several unsupervised learning techniques, we detect similarities in the beer tastes at the beginning of the drinking career of the users and analyze how they vary as they become more experienced. Lastly, we mathematically consolidate our findings with the use of statistics.

## Website
We created a website to present our results and we highly recommend you to [check it out](https://maximepoffet.github.io/rADAr-datastory/). On there, you will be able to play with interactive plots and you will meet the four protagonists of our data story: Jean-Michel IPA, Marcel Stouts, James Bland and Ada the Explorer!

## Instructions to run the notebook (Milestone 3)

To run the notebook `milestone3.ipynb` locally, be sure to add the file 'ratings.txt.gz' of the BeerAdvocate website in the data folder of the root repository. The file can be found on the [2022 ADA datasets webpage](https://go.epfl.ch/ada22_datasets). We specified every python package needed in order to run the notebook in the first cell of it. Make sure to have them all downloaded and updated.


## Research Questions
- Is there a beer category that serves as a gateway category?
- What are the common characteristics between the first beers users decide to rate?
- Do people with a similar initial beer taste follow a common path? When and why do their paths split? 
- Are there some beer categories where people eventually all end up in? 
- There are two ways to rate a beer. Either the final grade of a beer is a weighted average of five different criteria (such as appearance, palate or taste), or it is a single appreciation grade. Detecting nuances in the beers is one possible sign of user expertise and we want to analyze if users tend to give more detailed ratings through time or not. 

## Data sets used

- **beers.csv**
contains informations about every beer that users can rate on the respective website, e.g. its name, its average rating on the website or the total number of ratings it received. 
- **users.csv**
contains informations about every user that was active on the website, e.g. his username, the place where he lives or the number of ratings he submitted on the website.
- **ratings.txt.gz** keeps track of every rating submitted on the website between 2001 and 2017. A rating is composed of five different criteria: appearance, aroma, palate, taste and overall impression. The user can also further elaborate his feelings by leaving a comment in form of a small text.

## Team rADAr
- Leandre Castagna
- Pascal Epple
- Maxime Poffet
- Thibaud Trinca 

#
## <div align="center">  :arrow_down: **Milestone 2 Infos** :arrow_down: </div>


## Methods
**Step 1: Explore RateBeer dataset**
- Preprocess the dataset in the same fashion as the BeerAdvocate dataset. 
- Gain insights on the data and check for possible difference with the BeerAdvocate dataset.
- Decide if it is possible to combine both datasets or if it is better to use the RateBeer dataset as a control website.

**Step 2: Continue exploring the different datasets**
- Think about new data representation techniques that would help to gain insights on the data
- Come up with new interesting and meaningul visualizations
- Determine which visualizations techniques would nicely render on the final website

**Step 3: Create an efficient data preprocessing pipeline**
- Determine solid criteria for filtering valid US users based on number of ratings and time spacing between ratings.
- Work with different metrics representing user activeness of a user. 
- Come up with different metrics representing time spacing between ratings.

**Step 4: Explore feasibility of observational study**
- Determine an initial similarity measure for two users. 
- Compare the respective paths of the matched users.
- Coming up with interesting research questions (and try to answer them) such as: When do the paths split? Can we determine reasons behind them taking separate paths? What are the common characteristics of people that went on the same path?

**Step 5: Explore feasibility of "decision" trees**

_(Not really a decision tree: level $i$ of the tree represents the categories users rated in their $i$-th rating. Number of nodes per level is therefore limited to 15.)_
- Determine if method is interesting to pursue
- Gain insights on the data by comparing the different paths taken by users, determining "heavy" or "hot" nodes in the graph, check total number of final leaves.

**Step 6: Graph Mining**
- Continue to improve the network representation of the data, test different edge weights and incorporate user ratings into the network.
- Run, test and find different graph mining algorithms. Methods we already have in mind: Louvain algorithm, Girvan-Newman Algorithm.
- Analyze and present insights gained from the above analysis

**Step 7: Improving graph visualization**
- Look for other libraries that allow to visualize graphs.
- Adapt the code to every library and present the visualizations to the others.
- Check feasibility of implementing a graph visualization tool from scratch.

**Step 8: Redaction of the final data story**
- Think about the plot of the final data story
- Start to write the final text and incorporate data visualizations 

**Step 9: Start building the final website**
- Get familiar with GitHub pages
- Look for interesting templates that we could use

## Timeline

- 25.11.22: Work on HW2, Steps 2, 3, 6
- 02.12.22: **Deadline Homework 2**
- 09.12.22: Steps 1, 4, 5
- 16.12.22: Steps 7, 8, 9
- 23.12.22: **Deadline Milestone 3**

## Organization within the team

- Leandre: Steps 1, 3, 7, 8
- Maxime: Steps 2, 4, 6, 9
- Pascal: Steps 4, 5, 8, 9
- Thibaud: Steps 3, 5, 6, 9



