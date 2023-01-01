
<a id="toc"></a>

## <p style="background-color:#9d4f8c; font-family:newtimeroman; color:#FFF9ED; font-size:150%; text-align:center; border-radius:10px 10px;">CONTENT</p>


* [CONTEXT](#0)
* [About The Dataset & Atributes](#00)
* [Instructions](#000)
* [Importing Libraries Needed In The Case Study](#1)
* [Insights of Data](#2)
* [Data Preparing for Visualization](#3)
* [Making Decision for Best Strategy with A/B Testing](#4)
* [Conclusion](#5) 


<a id="toc"></a>

## <p style="background-color:#9d4f8c; font-family:newtimeroman; color:#FFF9ED; font-size:150%; text-align:center; border-radius:10px 10px;">CONTEXT</p>

<a id="0"></a>
<a href="#toc" class="btn btn-primary btn-sm" role="button" aria-pressed="true" 
style="color:blue; background-color:#dfa8e4" data-toggle="popover">Content</a>

A/B testing, one of the most common control methods, is generally preferred to use optimization in digital and web marketing strategies.

As a result of the important market analyzes of the team members responsible for market research in our team, we reduced the number of alternatives to two, and now we need to make a decision for these two alternative options.

It allows decision makers to choose the best design for a website or service by looking at the analysis results that the Data Science team has done.

<a id="toc"></a>

## <p style="background-color:#9d4f8c; font-family:newtimeroman; color:#FFF9ED; font-size:150%; text-align:center; border-radius:10px 10px;">About The Dataset & Atributes</p>

<a id="00"></a>
<a href="#toc" class="btn btn-primary btn-sm" role="button" aria-pressed="true" 
style="color:blue; background-color:#dfa8e4" data-toggle="popover">Content</a>

Typically web and digital marketing datasets are proprietary and consequently hard to find among publicly available data. However, 
Kaggle which is a platform have open datasets shared by accounts  has made this dataset containing actual transactions. The dataset is on the site (https://www.kaggle.com/datasets/ilkeryildiz/example-dataset-for-ab-test), where it can be found by the title "Example Dataset for A/B Test".

**Attribute Information:**

**``Campaign Name:``** The name of the campaign.<br>
**``Date:``** Date of the record.<br>
**``Spend:``** Amount spent on the campaign in dollars.<br>
**``of Impressions:``** Number of impressions the ad crossed through the campaign.<br>
**``Reach:``** The number of unique impressions received in the ad.<br>
**``of Website Clicks:``** Number of website clicks received through the ads.<br>
**``of Searches:``** Number of users who performed searches on the website .<br>
**``of View Content:``** Number of users who viewed content and products on the website.<br>
**``of Add to Cart:``** Number of users who added products to the cart.<br>
**``of Purchase:``** Number of purchases.<br>

Two campaigns were performed by the company:

   **``1.Control Campaign``**<br>
   **``2.Test Campaign``**

As a result, we will perform A/B testing to find the best campaign for the company to get more customers.


## <p style="background-color:#9d4f8c; font-family:newtimeroman; color:#FFF9ED; font-size:150%; text-align:center; border-radius:10px 10px;">Instructions</p>

<a id="000"></a>
<a href="#toc" class="btn btn-primary btn-sm" role="button" aria-pressed="true" 
style="color:blue; background-color:#dfa8e4" data-toggle="popover">Content</a>

**In this case we'll handle with the following steps:** 

- **Step 01.** Checking out of the DataFrame.<br>
- **Step 02.** Understanding to Insights of Data<br>
- **Step 03.** Be ready for Visualization<br>
- **Step 04.** Making Decision<br>
- **Step 05.** Summarizing<br>