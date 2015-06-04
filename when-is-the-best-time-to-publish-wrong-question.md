#### When is the best time to publish? Wrong question. {.metabar-drawerTitle}

It’s by far the most common question we hear. “When is the best time to publish on Medium?” (That is, in order to maximize [total time spent reading](https://medium.com/data-lab/mediums-metric-that-matters-total-time-reading-86c4970837d5), which is our focus at Medium.) Now we have an answer:

### It just doesn’t matter. {#0161 .graf--h3 name="0161" data-align="center"}

### At all. {#f4fa .graf--h3 name="f4fa" data-align="center"}

What *does*matter are two things:

1.  How much effort you put into writing something engaging
2.  How many followers you have

Once you account for those two factors, the publish time makes no difference. I’ll walk through the ten charts that prove it.

* * * * *

#### 1 | Publish Times {#5953 .graf--h4 .graf--first name="5953"}

The first thing we can examine is when posts are published. Here are all posts grouped by 3-hour publish time intervals. *(Note: all the charts in this analysis exclude the top 1% of posts because they skew the numbers and are even less correlated with publish timing.)*

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*_6CG4rO-m59OXKYDKvb4Tw.png)

The results aren’t too surprising.

-   Peak publish hours are 6am-3pm PST, with about 25% more posts published during that time frame.
-   Peak publish days are weekdays, with about 50% more posts published on weekdays than on weekend days.

* * * * *

#### 2 | Average Total Time Read (TTR) {#ed4f .graf--h4 .graf--first name="ed4f"}

Next we can look at average [total time read (TTR)](https://medium.com/data-lab/mediums-metric-that-matters-total-time-reading-86c4970837d5) per post published during each interval.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*j2fBRMSuGTXxYauhK02Shw.png)

“Ah-ha!,” you might say, “posts published during peak traffic hours *do*perform better.”

Yes, that’s how it seems at first. The difference is striking too: peak-time posts average more than triple the TTR of off-peak posts.

But! Not all posts are created equal.

* * * * *

#### 3 | Average Word Count {#b569 .graf--h4 .graf--first name="b569"}

To start exploring how these posts differ, let’s consider word count.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*TPx4aapl71tMobV30YNo5A.png)

The peak-time posts are consistently longer on average. This surprised me — why would the publish time relate at all to post length? I’ll return to this in a moment, but first we have a possible explanation: these posts might have more TTR simply because they take longer to read. We can check by normalizing for word count.

* * * * *

#### 4 | Average TTR per Word {#9357 .graf--h4 .graf--first name="9357"}

Instead of TTR per *post*published, here’s TTR per *word*published.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*NYlQ_I_ZBuEi68qj6pPUBQ.png)

We see the same pattern. After accounting for post length, peak-time posts still have more TTR on average.

But now we have a new question. Why are these peak-time posts longer? Maybe it’s the result of something else: quality. If these posts are somehow *better*, that could explain both why they tend to be longer and why they have more TTR on average. Unfortunately, it’s tough to quantify something as subjective as quality, but one possible proxy is how much time the author spent working on the post.

* * * * *

#### 5 | Average Drafting Time {#f4f9 .graf--h4 .graf--first name="f4f9"}

We can use the time authors spend in the writing editor to estimate the average total drafting time per post.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*CC-ITaBBm9CndJ4UuOPv2Q.png)

Again, it follows the same pattern. Since this could also be a result of the higher word counts, we need to normalize for that.

* * * * *

#### 6 | Average Drafting Time per Word {#235d .graf--h4 .graf--first name="235d"}

Here’s the average drafting time per word.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*2b9KPCNvD184u9UHCBLHCg.png)

Now we’re starting to see a clearer picture. Not only are the peak-time posts longer, but the authors also spend more time writing each word. This further supports the idea that these posts are higher quality. We can check if it explains the higher TTR by normalizing for time spent drafting.

* * * * *

#### 7 | Average TTR per Drafting Time {#672e .graf--h4 .graf--first name="672e"}

Here’s the average TTR minute per drafting minute, a sort of ROI on drafting time.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*k6MD_5LohhvmU7_48WZa3g.png)

We still see the same pattern, but it’s less pronounced. Compared with the original chart, normalizing for drafting time removed about one third of the peak vs. off-peak difference.

Drafting time isn’t the only proxy for “quality,” though. Another possibility is that when authors write great content, they start building up a following.

* * * * *

#### 8 | Average Followers {#46dc .graf--h4 .graf--first name="46dc"}

For every post published, here are the average number of followers that the author has on Medium.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*xoLydIOfzfqShpQo5wI2iQ.png)

Although clunkier, the same pattern is still there; authors who publish during peak times tend to have about twice as many followers on average. We can normalize for this.

* * * * *

#### 9 | Average TTR per Follower {#57be .graf--h4 .graf--first name="57be"}

Here’s the total TTR per follower of the author.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*z29dT7uBTANgR8gWOX7WRQ.png)

Finally we have broken the pattern! The followers appear to drive most of the original pattern. Still, the TTR seems to consistently dip during off-peak hours. Let’s try accounting for drafting time too.

* * * * *

#### 10 | Average TTR per Follower, per Drafting Minute {#7211 .graf--h4 .graf--first name="7211"}

Here’s the full normalization, taking the average TTR per follower and dividing it further by drafting minute.

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*3xNreAi1dIrS1Tpt0IBkug.png)

Now the peak vs. off-peak is fully removed, and we have our answer!

> After normalizing for the number of followers and the time spent drafting, there is no pattern between publish time and total TTR.

* * * * *

#### So what’s going on? {#ebd5 .graf--h4 .graf--first name="ebd5"}

\

On average, it’s true that posts published during peak hours (6am — 3pm PST on weekdays) tend to perform better. But these posts are also different:

-   Peak-time posts tend to be longer
-   Peak-time posts tend to take more time to write (per *word)*
-   Peak-time posts tend to have authors with more followers

So these are higher-effort posts with authors who interest more people. In other words, they’re probably higher quality. After normalizing for these factors, we find that the publish time no longer makes a difference.

So, back to the original question — when is the best time to publish? It doesn’t matter!

### What really matters is writing good stuff and, in turn, building a following. {#8ce5 .graf--h3 .graf--last name="8ce5" data-align="center"}
