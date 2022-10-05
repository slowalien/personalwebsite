---
date: "2021-09-12T00:00:00Z"
external_link: ""
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/Mf23RF8xArY)'
  focal_point: Smart
  preview_only: false
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/renkai_ma
slides: 
summary:  A project I **facilitate** with the PI, Dr. Yubo Kou to understand how esports gamers experience punishments issued by moderation systems, how they reason about moderation mechanisms, and how they adjust their future behaviors.
tags:
title: Online Community Moderation
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
### This paper is under review:
## A study of Esports Governance in League of Ledgends (*this is a tentative alternative title*)

### | My role: 
- Data collection and analysis
- Theoretical development and partial writing

### 1. Problem Statement
Esports, like traditional sports, face governance challenges. Like traditional sports such as basketball and football, esports faces governance challenges such as foul play, aggressive behaviors on competitive scene, and match fixing, and has the need to govern its participants such as professional players and teams. 

However, the esports industry has seen various attempts at governance structure but is yet to form a consensus and relatively less attention has been paid to how esports authorities interpret and enforce rules in their governance ecosystem. 

### 2. Research Question
##### RQ1: What behavior is conceived by the game publisher as rule breaking?
##### RQ2: How do contextual factors influence rule enforcement?
* RQ2.1: How does the location of rule breaking influence rule enforcement?
* RQ2.2: How does the time of rule breaking influence rule enforcement? 

### 3. Methods
* RQ1 - Content analysis on the online archive data

* RQ2 - A series of statistical analysis: Cramer’s V, Pearson's correlation, and Kruskal-Wallis H test on the content analysis results

### 4. Findings
#### 4.1 Qualitative Findings
#### 11 types of ruling-breaking behaviors corresponded to different penalty severity.

{{< figure src="wider version.png" title="Frequencies of Rule Breaking Behaviors from August 2012 to June 2021" >}}

#### 4.1 Quantitaitve Findings
#### 4.1.1 Contextual factors influence rule enforcement
The quantitative findings unpack the relationship between contextual factors and rule enforcement in Riot’s competitive rulings. In each competitive ruling, Riot determined the type of rule breaking behavior, and then issued a penalty. Next, we uncover how contextual factors are associated with penalty severity and then probe the internal relationship of penalty severity. Finally, we verify the impact of region and perpetrator identity on the distribution of penalty severity.

#### 4.1.2 Region matters in rule enforcement
We found a moderate/medium association between region and three variables, including year, punishment hierarchy, and if fined (Cramer's V coefficient, 0.3 < Φc < 0.5). This result suggested that each region might proportionally have its different dominated punishment hierarchy score and adjudication of fine, released by the game publisher in a specific year.

{{< figure src="vresult.png" title="Cramer's V results" >}}

##### Kruskal-Wallis (K-W) H test
To probe the second research question deeper, we ran independent-samples Kruskal-Wallis (K-W) H test to uncover how region affects the distribution of penalty hierarchy. We found that at least one region’s penalty hierarchy distribution was significantly different from other regions with the K-W test result, H (11) = 103.82, p-value < 0.001. However, this result did not inform us where the difference between different regions’ penalty distribution appeared. We thus conducted the post-hoc test, the Dunn-Bonferroni method, to generate a pairwise comparison between regions and penalty hierarchy scores, as shown below. To maintain a lower type-I error, the multiple p-values of each pair of regions’ penalty hierarchy have been adjusted to be adjusted coefficients through Bonferroni error correction.

{{< figure src="htest.png" title="Pairwise comparison of penalty hierarchy distribution in regions after post-hoc test" >}}

#### 4.1.3 Penalties are progressively harsher on a yearly basis.
We further ran the Pearson's correlation on all ordinal and ratio variables to uncover the linear relationship inside penalty severity and year, as shown in Table 4. We found a weak positive correlation between year and punishment hierarchy (Pearson r = 0.15, p-value < 0.01), implying that the game publisher has progressively released severer penalties over the years. Also, we found that inside of penalty severity, the fine adjudication had weak positive correlation with penalty hierarchy (r = -0.38, p-value < 0.01), penalty quantity per perpetrator (r = 0.21, p-value < 0.01), and fine amount (r = 0.13, p-value = 0.002). This finding suggested that when a game publisher issued a lower level of penalty, it was more likely to appear with a fine adjudication. Also, when a perpetrator received a fine adjudication with a specific fine amount, they are more likely to have more than one penalty. This suggested that fine adjudication more likely acted as a joint penalty with other heavier ones. Collectively, these findings suggest the increasing severity of penalty over the ten-year period.

{{< figure src="corr.png" title="Pearson's Correlation results" >}}

{{< figure src="Scatter Plot (time series) of Penalty Hierarchy.png" title="Scatter Plot (time series) of Penalty Hierarchy" >}}

#### Summary
We showed that rule enforcement in LoL esports is not static but highly contextualized. The severity of penalty correlates with several contextual factors such as year and region.

### 5. Discussions
* We identified several conspicuous characteristics of rule enforcement in the esports governance of LoL.

* The behavioral scope rule enforcement concerns is far-reaching.

* The rule enforcement in LoL esports is highly contextual.

* The rule enforcement in LoL esports is also dynamic and evolving


---
