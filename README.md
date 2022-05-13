# Google-Capstone-Project
This repo contains the files of capstone project in Data Analytics, which is made by using **Spreadsheets, Excel, R, SQL and Tableau.

Starting with the introduction, I was given a scenario where I was a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The company's future success depended on increasing maximizing the number of annual memberships. Therefore, my team wanted to understand how Casual riders and annual members use Cyclistic differently.

The first thought that popped into my head after reading the scenario was,

"This is an easier analysis than what I have done in the past".
**Well, I couldn’t be more wrong.

Before we begin, I’d like to point out that the data in this case study covers the period from June 2020 to May 2021.

Now let’s get started!

**Details about the company**

Cyclistic started a successful bike-sharing program in 2016. Since then, the program has evolved to include a fleet of 5,824 bicycles that are geo-tracked and locked into a network of 692 stations across Chicago. Bikes can be unlocked and returned to any other station in the system at any time.

Until recently, Cyclistic’s marketing strategy has focused on raising general awareness and appealing to a wide range of consumers.

The flexibility of its pricing plans, which included single-ride passes, full-day passes, and annual memberships, was one strategy that helped make these things possible.

**Cyclistic’s customers are broadly classified into two categories: -**
* Customers who purchase single-ride or full-day passes are referred to as **Casual riders.**
* Customers who purchase annual memberships are **Cyclistic members.**
**The Conflict**
Our finance analysts concluded that annual members are much more profitable than Casual riders and my manager, Lily Moreno believed that maximizing the number of annual members will be key to future growth. She also believed that rather than creating a marketing campaign that targets all-new customers, there is a very good chance to convert Casual riders into members.

To sum up, we had to figure out a way to convert the Casual riders into members.

**But, how are we going to do that?

**My Role**
This is where I come into the picture, I needed to identify the trends by analyzing Cyclistic’s historical bike trip data.

But before analyzing the data, I asked a few questions to myself: -
* **How do annual members and Casual riders use Cyclistic bikes differently?
* **Why would Casual riders buy Cyclistic annual memberships?
* **How can Cyclistic use digital media to influence Casual riders to become members?

These questions helped me to give direction and structure to my analysis.
**The Analysis
Let's look at the average ride lengths first,
![1_ziUV8wgUPU5EBWzGrzGRFQ](https://user-images.githubusercontent.com/87076914/168316739-f8213acc-4758-4b6b-86e7-2f25993324a4.png)
Image by the Author | This chart shows the average ride lengths

We can observe that the average ride length for all users is **23 minutes,

while Cyclistic Members only rode for **15 minutes** on average, Casual riders rode for **35 minutes** on average, a **20-minute** difference from members.
**Now Let’s take a look at the Cyclistic Userbase in more detail.
![1_dfsv5a_6dN-xk1sumRDvKg](https://user-images.githubusercontent.com/87076914/168317027-fd92f548-d308-466d-ab1a-c1ead83fba8c.png)
Image by the Author | This chart shows the overall rides by users

We can observe here that in the previous twelve months, Cyclistic provided a total of **4.07 million** rides to its customers, with Cyclistic members accounting for **2.36 million** rides and Casual riders accounting for **1.71 million** rides.
This indicates that Cyclistic members ride **1.38 times** as much as Casual riders.
A **simultaneous decrease** in the number of rides by Casual riders and an **increase in the number of rides** by Cyclistic members would imply that the **Casual riders are buying the membership** and converting into Cyclistic Members.
**Now coming onto our next chart, it illustrates the three types of bikes and the number of rides taken on them.
![1_q8JSStUDHncLeYuTAaqp_Q](https://user-images.githubusercontent.com/87076914/168317504-49a6b022-a29d-48f2-a3cc-40012b45ad3d.png)
Image by the Author | This chart shows the number of rides by bike type

Starting with the **Classic Bikes**, their popularity is identical to **Electric bikes** with **0.85 million rides** accounting for **20.71%** of total rides. Casual Riders used Classic bikes for only **0.27 million rides**, accounting for **6.52 %** of total rides, whereas Cyclistic Members used Classic bikes for **0.58 million** rides, accounting for **14.19 %** of total rides.

Next are the **Docked Bikes**, they were the most popular bikes of them all with **2.34 million rides** accounting for **57.48%** of total rides. While Casual Riders used Docked Bikes for **1.07 million rides**, accounting for **26.37 % of total rides**, Cyclistic Members used Docked Bikes for **1.27 million rides**, accounting for **31.11 %** of total rides,

Then there are the Electric Bikes, which were identically popular as classic bikes but very less popular than Docked Bikes with **0.88 million rides** accounting for **22.35 %** of total rides. While Casual Riders used Electric Bikes for only **0.37** million rides, accounting for **9.17 %** of total rides, Cyclistic Members used Electric Bikes for **0.51** million rides, accounting for **12.64 %** of total rides.

To summarise this chart, we can conclude that the majority of members and Casual riders prefer **Docked Bikes** to the other two types of Bikes.

**Now diving further into the behavior of the Casual riders,
![1_LQbSMwOk07HUkBP42Iyi5A](https://user-images.githubusercontent.com/87076914/168318644-545cf0e7-2c62-4d2f-b0f7-595c394c71d6.png)
Image by the Author | This chart shows the number of rides of casual riders by day of the week

This chart shows that **Monday** was the **busiest day** of the week, accounting for **23.19 %** of total rides. Implying that after the weekend, Casual riders prefer to use Cyclistic to commute from home to work or from work to home.

As the week progressed, **Tuesday** was the **second busiest day** of the week, accounting for **19.29 %** of total rides. Although Casual riders did not use Cyclistic as frequently on Tuesday as they did on Monday, Tuesday still accounted for a significant portion of the total rides.

Casual riders took a **considerable drop** in the number of rides they took on Wednesday, accounting for only **11.01 %** of all rides, a drop of **8.28 %** from Tuesday.

As the week progressed, the number of rides on **Thursday and Friday** were nearly **identical to those on Wednesday**, with **Thursday** accounting for **10.20 %** and Friday accounting for **10.67 %** of total rides.

On the weekend, there was an increase in the number of rides, accounting for **11.21 %** of total rides on **Saturday**, and a considerable increase on Sunday, the third busiest day of the week, accounting for **14.43%** of total rides.
**Now it’s time to break down the rides by seasons,
![1_cMaDsvqrfNYIh2SFB2yb-g](https://user-images.githubusercontent.com/87076914/168319395-71ca4883-a478-4312-ac61-1b87a9579143.png)
Image by the Author | This chart shows the number of rides by season

**Winter** had the **fewest rides** of all the seasons, accounting for only 6.83% of total rides, this implies that customers dislike riding their bikes in the cold temperatures. In winters, Cyclistic members rode **9.31 %** of their total rides, whereas Casual riders rode only **3.41 %** of their total rides.

**Spring** was the **third busiest season**, accounting for **26.94 %** of all rides, implying that when the weather warms up, customers begin to take more trips. In Spring, Cyclistic members rode **26.26 %** of their total rides, whereas Casual riders rode **27.86 %** of their total rides.

**Summers** was the **busiest season** for Cyclistic, accounting for **37.24 %** of all rides. The number of rides peaked in this season, indicating that customers preferred to travel on bikes in warm weather. In Summers, Cyclistic members rode **34.04 %** of their total rides, whereas Casual riders rode **41.66 %** of their total rides.

**Autumn** was the **second busiest season**, accounting for **29.0 %** of all rides. Although the number of rides decreased as the season transitioned from summer to winter, a lot of customers wanted to ride bikes in this season. In Autumn, Cyclistic members rode **30.4 %** of their total rides, whereas Casual riders rode **27.06 %** of their total rides.
**Let’s now analyze the number of rides by the time of day,![1_ULvrvh87kgdeO4F0Ipadjg](https://user-images.githubusercontent.com/87076914/168320168-e58d52a1-a335-4ac1-81d7-ef012bd387a2.png)
Image by the Author | This chart shows the number of rides by the time of day

The **least popular time** to go for a bike ride was at **Night**, accounting for only **12.32 %** of all rides. This could be because the majority of people are sleeping during this time. In the night, Cyclistic members rode **10.72 %** of their total rides, whereas Casual riders rode **14.55 %** of their total rides.

The **second most popular time** to go for a bike ride was in the **morning**, which accounted for **27.37 %** of all rides. This indicates that customers are more active, riding their bikes commuting to school, college, or work. In the Morning, Cyclistic members rode **30.46 %** of their total rides, whereas Casual riders rode **23.07 %** of their total rides.

Bike rides were **most popular** in the **afternoon**, accounting for **40.36 %** of all rides. The majority of Cyclistic customers choose to go for a bike ride in the afternoon, perhaps because they are returning home from school or college. In the Afternoon, Cyclistic members rode **39.16 %** of their total rides, whereas Casual riders rode **41.97 %** of their total rides.

Bike rides in the **evening were also quite popular**, accounting for **19.93%** of all rides. This could indicate that people used Cyclistic bikes to commute back to their homes from their day jobs. In the Evening, **Cyclistic members** rode **19.65 %** of their total rides, whereas **Casual riders** rode **20.3 %** of their total rides.
**The Conclusion
I came to the following conclusions after completing all of the analyses: -

* Casual riders rode **20 minutes** more than the members on average.
* Both casual riders and members tend to **like docked bikes** more than the other two bikes.
* Casual riders tend to make the **most of their trips on Mondays and Tuesdays**
* **Summer** is the **most popular season**, so it has the **highest potential** for converting casual riders into members.
* The majority of casual riders **rode in the afternoon**, however, **morning and evening** combined also accounted for a **huge number of rides.**
**The Recommendations
Now, to end this case study, here are my recommendations for the Cyclistic marketing team: -**

* Capture the huge market share of casual riders by **personalizing discounts** and **perks** in the membership program to their tastes, preferences, and riding habits.
* **Emphasize the benefits** of membership, such as discounts and privileges, to casual riders.
* **Reward existing members** to share their personal stories about how they use Cyclistic and how it has become a **vital part** of their lives on social media **using a hashtag to create a sense of community.**

**Thanks for Reading!
I hope that you find this case study interesting. :)
