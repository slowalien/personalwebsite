---
abstract: To manage user-generated harmful video content, YouTube relies on AI algorithms (e.g., machine learning) in content moderation and follows a retributive justice logic to punish convicted YouTubers through demonetization, a penalty that limits or deprives them of advertisements (ads), reducing their future ad income. Moderation research is burgeoning in CSCW, but relatively little attention has been paid to the socioeconomic implications of YouTube's algorithmic moderation. Drawing from the lens of algorithmic labor, we describe how algorithmic moderation shapes YouTubers' labor conditions through algorithmic opacity and precarity. YouTubers coped with such challenges from algorithmic moderation by sharing and applying practical knowledge they learned about moderation algorithms. By analyzing video content creation as algorithmic labor, we unpack the socioeconomic implications of algorithmic moderation and point to necessary post-punishment support as a form of restorative justice. Lastly, we put forward design considerations for algorithmic moderation systems.
authors:
- admin
- Yubo Kou
date: "2021-07-23T00:00:00Z"
doi: "10.1145/3479573"
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/VLzAkbs5afg)'
  focal_point: ""
  preview_only: false
projects:
- a-yt_mod
publication: "*PACM  on  Human  Computer  Interaction*, Vol.  5, CSCW2"
publication_short: In *CSCW' 2021*
publication_types:
- "2"
publishDate: "2021-07-23T00:00:00Z"
slides: 
summary: We uncover and discuss the socioeconomic implication of algorithmic content moderation on YouTube.
tags:
- Source Themes
title: "“How advertiser-friendly is my video?”: YouTuber’s Socioeconomic Interactions with Algorithmic Content Moderation"
url_pdf: https://www.researchgate.net/publication/355078337_How_advertiser-friendly_is_my_video_YouTuber's_Socioeconomic_Interactions_with_Algorithmic_Content_Moderation
#url_poster: '#'
url_project: "a-yt_mod"
url_slides: "slides/cscw2021/Ma_Kou_CSCW2021.pdf"
#url_source: '#'
url_video: 'https://youtu.be/rv-GgvM43_8'
---
### Please watch the video presentation here:
{{< youtube rv-GgvM43_8 >}}
---

### 1. Problem Statement
"YouTuber," i.e., content creator nowadays could be a profitable job for many people who aim to earn money (primarily advertising income from the platform) from their content creation and sharing. YouTube decides this income from the viewing times and viewer engagement rates of videos, constituting the **socioeconomic** content moderation.

{{< figure src="income.png" title="Socioecnomic Content Creation on YouTube" >}}

But not all video content is advertiser-friendly or acceptable to communities. When YouTube deems a YouTuber's video as unacceptable, YouTube will **demonetize** a YouTuber's videos or channels, eventually denying them from earning more future ad revenue through placing limited or no ads on the videos.

As social media uses various algorithms (e.g., machine learning) to implement content moderation, little attention has been paid to how users interact with algorithmic moderation and their post-hoc experience. Especially for the users perform profitable content creation, few studies have understand how they receive, perceive, and react to algorithmic content moderation. This study aims to approach this research gap in the context of **socioeconomic** implications of YouTube moderation. 

### 2. Research Question
##### How do YouTubers interact with the socioeconomic side of algorithmic moderation? 

### 3. Methods
* We scraped online discussion data from the subreddit, r/youtube through a bag of keywords related to content moderation of YouTube. The final dataset contained 2,779 threads with 60,310 individual comments. 

* We inductively ran thematic analysis on the online discussion data. 

### 4. Findings
a. **Being Confused about Algorithmic Opacity**: YouTubers who experienced algorithmic punishments felt confused and had no clues of how algorithms made decisions. Even if the adjudication of a moderation case is clear-cut to most people, YouTubers who received the penalty could experience it differently and feel hard to retore its **algorithmic transparency**.

b. **Managing Algorithmic Precarity**: Algorithmic moderation engenders the work uncertainty of video content creation and how YouTubers manage their precarity by diversifing their income.

c. **Learning and Applying Algorithmic Know-How**: YouTubers collectively made sense out of algorithmic punishments, developing, and disseminating algorithmic knowledge of YouTube moderation. Specifically, they shared and analyzed their punishment experiences to speculate about moderation algorithms, which in turn informed operations of repairing their past moderation and avoiding future moderation.

{{< figure src="str.png" title="The Labor of YouTubers Conditions in YouTube's Algorithmic Moderation" >}}

### 5. Discussion and Design Considerations

We shed light on the labor of video content creators and how they handled moderation punishments. We showed how moderation algorithms crafted YouTubers’ content creation work, engendering a necessary form of algorithmic labor to comply with moderation algorithms on YouTube and make their videos “advertiser-friendly.”

#### 5.1 Design Considerations for Alglorithmic Moderation Systems
* Transparency of algorithmic decision-making process: detailed moderation explanations.

* Potentially Reimbursement given false-positive moderation decisions: especially for those who reversed false-positive moderation decisions.  

* More advanced tools for channel moderation to prevent unacceptable viewer comment from incurring moderation decisions on YouTubers. 


