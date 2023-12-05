# CMSE202-Project


Project Group : NYC Traffic Flow


Group members : Vibu Darshan, Yogit Goyal,Thong Van,Connor Croft

Project Abstract

In this comprehensive study, we set out to evaluate and quantify road congestion in New York City by leveraging taxi trip data as a surrogate measure for real-time traffic conditions. Our analysis hinged on a robust dataset containing detailed trip information, including Pickup Location ID (PULocationID), Drop-off Location ID (DOLocationID), trip distance, and fare amount. This information provided a nuanced understanding of travel patterns and costs associated with taxi rides, allowing us to develop an innovative methodology for gauging road efficiency between different locations within the city.

The core of our approach involved the establishment of a network representation of NYC, with nodes corresponding to unique PU and DO location IDs. Each edge in the network encapsulated the road segment connecting two locations, and our novel measure of road efficiency was derived by calculating the average efficiency of multiple trips between the same origin and destination. The resulting average efficiency was then inversely related to the weights assigned to the corresponding edges, providing a weighted network that encapsulates the varying efficiency levels of different road segments.

One of the key observations from our analyses was the correlation between trip distances and fares. Unsurprisingly, we found that longer trip distances tended to result in higher fares, but a notable additional factor was the impact of traffic conditions. Areas experiencing more traffic were associated with higher fares due to extended travel times, highlighting the dynamic relationship between distance, time, and cost in the taxi service ecosystem.

Our investigation into the spatial distribution of taxi and subway density unveiled Manhattan as a central hub of business and activity, evident in both the subway and taxi maps. The density of taxi ridership was particularly pronounced in areas with higher business activity, emphasizing the interplay between economic centers and transportation demand. Furthermore, our analysis shed light on the disproportionate representation of airports in taxi ridership data, suggesting a preference among tourists for taxi services over the subway, potentially due to perceived confusion or a less favorable reputation of the latter. The absence of train services at LaGuardia Airport (LGA) likely contributed to the reliance on taxis for airport transportation.

Commuter patterns also emerged as a significant aspect of our findings, with numerous taxi lines originating from the outer boroughs (Queens, Brooklyn, Bronx) and converging on Manhattan. This commuter-centric traffic flow underscores the crucial role of taxis in facilitating daily commutes for residents living in the outskirts of the city.

Analyzing subway lines, we observed a concentration of major lines traversing through Manhattan, creating a hub-and-spoke-like pattern. Notably, there was a dearth of direct subway connections between Queens and Brooklyn, contributing to increased taxi demand between these locations due to the relative inefficiency of existing subway routes.

Building upon our findings, we propose a set of actionable solutions to address road congestion in NYC. First and foremost, we advocate for a renewed focus on promoting subway usage. Subways offer a space-efficient and cost-effective means of transportation, particularly once constructed. To incentivize subway adoption, targeted efforts could involve improving subway accessibility, enhancing service frequency, and implementing strategies to mitigate perceived inconveniences.

Additionally, we propose the promotion of ridesharing initiatives as a means to decrease the weight of individual taxi trips. Encouraging friends, colleagues, or individuals traveling in the same direction to share taxi rides could contribute to a reduction in overall traffic volume.

Moreover, our project underscores the imperative to promote sustainability in transportation. As NYC grapples with traffic-related challenges, prioritizing green and innovative solutions becomes paramount. Investments in eco-friendly transportation alternatives, coupled with infrastructure improvements, can contribute to a more sustainable urban mobility landscape.

In conclusion, our project offers a comprehensive analysis of road congestion in New York City, leveraging taxi trip data to assess traffic conditions and uncover key contributors to congestion. Through innovative methodologies and insightful findings, we contribute to the ongoing discourse on urban transportation challenges. The proposed solutions emphasize the promotion of subway usage, ridesharing initiatives, and sustainability efforts to address the multifaceted issues associated with road congestion in the dynamic urban environment of New York City. Through these strategic interventions, we aim to inform policy decisions and contribute to the development of sustainable transportation practices for the benefit of both residents and visitors alike.

```python

```
