# ESPN API

[Video Tutorial](https://youtu.be/Z8pPmpFcKMo)

## Objective
Answering the fantasy football question: **does draft order matter in fantasy football**?

## Details
A breakdown of how I used the ESPN API to pull draft and matchup data from my fantasy football league history. This code is somewhwat personalized to my league's situation however it can be used as a template for how to pull and analyze data for your leauge.

- Pull data from two ESPN API views: mDraftDetail & mTeam for all the years
- Parse through the JSON formatted data into pandas DataFrame
- Merge DataFrame on unique IDs
- Visualize data

## Results

![Win Percentage by Draft Position](https://user-images.githubusercontent.com/29851231/188334157-db89c2e1-8368-49b1-9a30-535c09efe286.png)

The small size of our dataset means the results aren't statistically significant. However, we can see that the first few picks of the draft outperform the average marginally. The 8th pick has dramatically underperformed (15% less wins than average!), and the 9th pick is an outperformer.
