# KillerMatrix
#   Tracking Evil Across the Globe

Hey all you cool cats and kittens,

Recently I’ve felt like I completely dropped the ball on my professional development. After a particularly inspiring interview, I decided it was time to get stuck into a proper personal project.

Choosing what to work on took far longer than I’d like to admit. I knew I wanted to build something in Power BI, but I couldn’t settle on a dataset. I scrolled through Kaggle like it was TikTok, hoping something would spark joy. When that failed, I wandered over to r/PBI to see what people recommended for personal projects. Someone suggested using data related to your own interests or hobbies. Naturally, the moment I needed to think of my interests, my mind went completely blank - classic.

Eventually, I remembered that I’ve always been fascinated by true crime. So… why not build something around serial killers?

That’s when I found a website with exactly the kind of data I wanted. Unfortunately, there was no way to contact the owner - Facebook page gone, Twitter account deader than the Queen - so I turned to Copilot for help. Web scraping wasn’t an option due to API restrictions, but Wikipedia could fill in some of the gaps. Mint.

I started with a list of just over 400 serial killers. After cleaning the data, I narrowed it down to those with confirmed birth dates, since I wanted to explore whether there were any patterns related to zodiac signs or birth days.

With the model in place, I began creating the DAX measures that would drive the analysis - totals, averages, medians, Top N logic, dynamic titles, and conditional formatting. From there, I designed a multi‑page Power BI report that blends narrative and analysis. Each page focuses on a different angle: global patterns, country‑level profiles, and behavioural trends like zodiac signs and birth dates. I aimed for a clean, accessible layout with guided insights, interactive slicers, and consistent styling so the report feels cohesive and easy to explore.

# BIG THANKS TO 
Kaggle.com

Killer.cloud

SQLBI (Youtube)- Filter Top X, with "Others" Category

Access Analytic (YouTube) - Power BI Conditional formatting using Measures

r/PBI

Copilot

ChatGPT

# Screenshots 

![1 Home Page](https://github.com/user-attachments/assets/dbaa2ec5-81ef-480b-9f56-70baa44f04a1)

![2  Global Overview](https://github.com/user-attachments/assets/237450cc-4625-4f7e-a184-89ce231815fc)

![3  Top X Countries](https://github.com/user-attachments/assets/80a484ca-02fd-4ae8-8a57-a2d5e7de7ef6)

![4  Country - Colombia](https://github.com/user-attachments/assets/5b60fb8f-af79-4b09-994f-4a1139e6db24)

![4  Country - South Korea](https://github.com/user-attachments/assets/5f7e10e4-d466-43da-901d-d2a06bb22c13)


View the interactive Power BI report here:
[Open Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMmVjZGJhN2UtMDNlYS00NjUyLTljZmUtMzFiNTU5MjcxZDM1IiwidCI6ImQwNzA5Zjg0LTc5OTgtNGE3OS1iOGVkLTcyNTA1OWY5Y2I0MiJ9)


