# Road to beer experts: how do beer tastes evolve through time?

___Study of the evolution of beer tastes through time___


## Abstract

From our own experience, we can tell that our beer tastes have drastically evolved over the past 10 years. At first, we only drank Pils and found other styles of beer disgusting. Today, we can enjoy an IPA but are not yet satisfied when being served a Guinness.

By analyzing ratings submitted on BeerAdvocate and RateBeer, two of the largest beer rating websites, we want to determine if these shifts in beer taste are common to other people as well.

<!-- We could try to classify users into different categories, going from complete beginner to expert, based per example on the number of reviews a user has written. It would then be interesting to detect first how these people’s tastes differ from each other, but also if in the beginning an expert had the same tastes/drank similar beers as a complete beginner. By looking at the text reviews through time, we might also find that users develop a specific vocabulary and become more able to express their sentiment towards beer. -->


## Research Questions

- Is there a single gateway beer style?
- What are the common characteristics between the first beers the users decide to rate?
- How 
- Do people starting with a similar beer taste follow a common path? (Observational study? -> explore) 

## Proposed additional datasets / Data sets used ?

- beers.csv
- users.csv
- ratings.txt.gz

## Methods
**Step: Explore RateBeer dataset**
- Prepare the data-set to serve as control website for our findings

**Step: Continue exploring the different datasets and coming up with meaningul visualizations**

**Step: Explore possibility of observational study**
- Matching users with similar beer tastes at the beginning, same number of ratings through time and comparing their respective paths.

**Step: Create an efficient data preprocessing pipeline**
- Determine solid measures in order to justifiy the final data set of valid US users.
- How do we determine if a user is an expert or not.

**Step: Graph Mining**
- Louvain Algorithm:
- Girvan-Newman Algorithm
- Explore different weight definitions incorporating user ratings


**Step: Look for better graph visualization tools**

**Step: Redaction of the final data story**

**Step: Get familiar with GitHub pages and build the final website**

## Proposed timeline
*  
* 
* 02.12.22: **Deadline Homework 2**
* 23.12.22: **Deadline Milestone 3**



## Organization within the team: 

<table class="tg" style="undefined;table-layout: fixed; width: 342px">
<colgroup>
<col style="width: 164px">
<col style="width: 178px">
</colgroup>
<thead>
  <tr>
    <th class="tg-0lax"></th>
    <th class="tg-0lax">Tasks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">@epplepascal</td>
    <td class="tg-0lax">Come up with meaningful visualizations<br><br>Continue exploring the dataset<br><br>Develop the final text for the data story</td>
  </tr>
  <tr>
    <td class="tg-0lax">@castagnaleandre</td>
    <td class="tg-0lax">Develop the web interface<br><br>Analyze news website bias<br><br>Develop the final text for the data story</td>
  </tr>
  <tr>
    <td class="tg-0lax">@TicaGit</td>
    <td class="tg-0lax">Define topic of interests<br><br>Tune clustering<br><br>Develop the final text for the data story</td>
  </tr>
  <tr>
    <td class="tg-0lax">@maximepoffet</td>
    <td class="tg-0lax">Develop the web interface<br><br>Integrate datasets of all years<br><br>Develop the final text for the data story</td>
  </tr>
</tbody>
</table>

## Questions for TAs (optional)
Add here any questions you have for us related to the proposed project.