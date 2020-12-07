# An exploration of Ford GoBike data
## by Pamely ZANTOU

## Investigation Overview

In this investigation, we wanted to look for the relationship between Ford Gobike type of users, their travelled distance and rental duration.

## Dataset

The dataset consists of 183412 bikes rentals and 16 variables describing each rental. These variables provide information about bikes, rental duration, users' profile and bikes' stations. 8460 data points were removed from the analysis due to inconsistencies or missing information.
## Summary of Findings

- The distribution of the rental duration is highly skewed when plotted. So, we performed a log scale tranformation that results in a normal distribution with a peak at 500 seconds. We also plotted the square root distribution of the distance between start and end station. Actually, when plotted, the distance was highly skewed. But due to null distances and their large positive values we prefer a square root transformation. Then, we obtained a normal distribution at the end with a peak near 1600 meters.

- Rental duration and travelled distance have weak positive linear correlation before transformation. After performinga log transformation on duration and a square root transformation on distance, the relationship surprisingly appeared strong and almost linear.

- Plotting the total distance travelled per day revealed that users rent bikes mostly during business days especially on Thurdays. Added to the fact that adults (early, middle and mature) rents more bikes than teenagers and old people, we can think that adults travelled and spend more time with bikes than others. But unexpectedly, we found out that teenagers travel the most and spend more time with bikes despite the fact they are the least representative group in the dataset.

- The multivariate explorationg reinforces the earlier assumptions. On the one hand, teenagers spend more time with bike than adults. Ford could study in depth the travel needs of teens in order a design a marketing strategy towards them. On the other, adults (early, middle and mature) on a regular basis and more during business days. Regarding the most represente age group, this suggests that most of people Ford GoBike use the service for their ponctual daily travels, especially job-related one. Data on users' profession will help us have a more clear picture on that.


## Key Insights for Presentation

- In the course of our exploration we grouped users by age. Five groups have been ifentified: Teen (19-20), Early adult (20-35), Middle adult (35-50), Mature adult (50-80) and Late aldult (>=80). Plotting the proportion of users per age group reveals that teenagers and old people rent less bikes. Early adult rent the most, followed by middle adult and then mature adults.

- Plotting membership status shows that there are more subscribers than simple customers. This means that customers quickly adopt the service. This can be due to quality of service but also to the need of bikes in their daily travels to save time, money or just for wellness. 

- More male rent bikes than female and other genders people.

- Plotting the log scale duration and the square root scale distance produce an approximately a linear relationship. It comes out that most users rent bikes for 3000s (50 minutes) or less. maybe for one-off trips.

- Distance travelled and rental duration are both higher during business days with peak on Thursday. Therefore, people rent bikes more during business day. Considering the fact that Early Middle and Mature adults rent more bikes, we may think that renters user bikes for their ponctual reasons. For example, to get to work.

- There are more subscribers than customers for all genders.

- Teenagers ride more and spend more time with bikes than adults. Adults (early, middle and mature) use of bikes is very constant over time. This last, show that adults use bikes for periodic trips.
