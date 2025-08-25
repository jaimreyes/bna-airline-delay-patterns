
# Nashville International Airport Flight Delay Analysis

## Table of Contents

- ### Motivation
- ### Data Questions
- ### Problems & Hurdles
- ### Data Dictionary
- ### Tools

### Motivation

As the travel planner for my family, I always ensure that our vacations run smoothly. The most daunting part is finding a reliable airline that won't disrupt my vacation. Too many times I have booked flights with airlines that end up having frequent delays. It doesn’t matter as much when I am heading home, but it makes a huge difference when I am trying to get to my destination from Nashville. In those moments, all I can do is roll my eyes and take the blame for booking that airline. When it comes to travel, time is money. A delay can mean losing the time I have already paid for, whether it’s a night at a luxurious Airbnb or an excursion booked through Viator. Most of the time, I will not receive a refund for those bookings, and in many cases, the flights themselves are also non-refundable. I need to prioritize every moment while creating the best possible experience. 

As a wanderluster, I live for those days when I can step into a new world I’ve dreamed about visiting, and I treasure the memories I know I’ll talk about for years to come. The fate of my family’s vacation often rests on my shoulders, which is exactly why I became so interested in this project. Was I simply biased toward certain airlines when I booked? Or do some airlines truly have more frequent delays? In the end, answering this question wasn’t just about flights—it was about protecting the experiences, the joy, and the memories that make travel so meaningful for me and my family.

# Data Questions

* Which airlines servicing BNA experience the highest rates of flight delays?
* How do flight delay rates vary by season for airlines at BNA?
* How do flight delay rates vary by time of day for airlines at BNA?
* What led to these flight delays?

### Problems & Hurdles

#### Data Limitations

* I had to download raw flight performance data month by month for 2022–2024, which ended up being huge zipped datasets.

* The Bureau of Transportation Statistics (BTS) has several links and websites, but the data names and databases are not consistent, which made it tricky to navigate.

* Many carriers don’t report their on-time performance data.

* Small regional airlines (regional branded code-share partners) are not included in the datasets.

* Some database value names were unclear or misleading, which made cleaning the data more challenging than expected.

#### Data Handling Challenges

* Transferring data to Power BI was not easy, especially when uploading and sharing the dataframe.

* Working with large, inconsistent datasets was tough but also a really valuable learning experience.


### Data Dictionary

* Ontime Arrival Percent: The percent of flights that actually arrive on time.
* Late Flight: Any flight that arrives 15 minutes or more after its scheduled time.
* Air Carrier: Delays or cancellations caused by the airline itself, like crew issues, maintenance, fueling, or baggage handling.
* Extreme Weather: Severe weather events, such as tornadoes, blizzards, or hurricanes, that prevent safe flight operations.
* National Aviation System (NAS): Delays caused by broader factors like non-extreme weather, heavy traffic, airport operations, or air traffic control.
* Late-arriving aircraft: When a previous flight with the same plane arrives late, causing the next flight to be delayed.
* Security: Delays caused by things like terminal evacuations, security breaches, long screening lines, or equipment failures.
* Departure OTP: Measures how often flights leave the gate or runway within 15 minutes of their scheduled departure, showing how efficient the airline is on the ground (boarding, fueling, baggage, etc.).
* Arrival OTP: Measures how often flights land or arrive at the gate within 15 minutes of schedule, reflecting factors en route like weather, congestion, and air traffic.
- Key difference:
+ Departure OTP = how punctual flights leave.
+ Arrival OTP = how punctual flights arrive at their destination.

### Tools
* juptyer notebook
* python
* powerbi
### Link to Dashboard
