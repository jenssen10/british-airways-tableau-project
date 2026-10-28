# British Airways Customer Reviews Analysis

An interactive Tableau dashboard exploring British Airways customer reviews: how ratings vary by aircraft, over time, and by country, with a selector to switch between rating categories.

> Based on the project tutorial by Mo Chen on YouTube. [ADD LINK TO THE VIDEO]

## Live Dashboard

[(https://public.tableau.com/app/profile/jenssen.honore/viz/BritishAirwaysReviews_17924199462390/Dashboard2)]

![Dashboard preview](https://githubusercontent.com)




## Project Overview

This project analyzes passenger reviews of British Airways to see which parts of the experience customers rate highest and lowest, and how those ratings differ by aircraft type, month, and location.

## Data

- **Source:** [(https://github.com/mochen862/tableau-end-to-end-portfolio-project.git)]
- **Files:** `ba_reviews.csv` (review data) joined with `Countries.csv` (for the map)
- **Size:** 1324 reviews covering March 2016 to October 2023
- **Fields:**
  - *Review:* Header, Content, Author, Date, Trip Verified, Recommended
  - *Trip:* Aircraft, Route, Date Flown, Place, Seat Type, Traveller Type
  - *Ratings:* Overall Rating, Cabin Staff Service, Entertainment, Food & Beverages, Ground Service, Seat Comfort, Value For Money

## Dashboard Features

- **Metric selector:** a parameter that lets the viewer switch the charts between overall rating and each category (cabin staff, entertainment, food, ground service, seat comfort, value for money)
- **Map:** ratings by country
- **Trend by month:** how ratings move over time
- **Breakdown by aircraft:** which aircraft types score best and worst
- **Summary view:** headline numbers

## What I Did

Built following Mo Chen's tutorial [(https://www.youtube.com/watch?v=KlAKAarfLRQ&t=1s)]. In this project I:

- Joined the reviews data with a countries table to map ratings by location
- Created calculated fields and a parameter so the dashboard can switch between rating categories
- Built the map, monthly trend and aircraft views and combined them into one dashboard
- Added filters for traveller type, seat type, aircraft group, continent and date range
  

## Key Findings

- **Entertainment is the weakest part of the experience.** It averages just 1.4, well below food (2.4), value for money (2.8) and seat comfort (2.9). Cabin staff service scores highest of the categories at 3.3, followed by ground service at 3.0.
- **Larger long-haul aircraft rate better than smaller short-haul ones.** The Boeing 747-400 (4.7), 747 (4.4), 787 (4.4) and 777 (4.4) lead the overall ratings, while the Airbus A321 (3.6), A319 (3.8) and Boeing 777-200 (3.8) rate lowest. The 747-400's top score rests on only 97 reviews, so it is less certain than the A320's 4.3 across 263.
- **Ratings are volatile month to month with no clear long-term trend.** Monthly averages swing widely between 2016 and 2023, with sharp dips around 2020-2021 and a spike in 2022. Months with few reviews likely exaggerate these swings.
- **Review volume is uneven.** The most-reviewed groups are "Various" aircraft (329) and the A320 (263), so overall averages are driven mostly by short-haul and mixed-fleet reviews.

## Tools

- Tableau Desktop / Tableau Public
  

## Repository Contents

| File & Description |

| `British Airways Reviews.twbx` | Packaged Tableau workbook (includes the data extract) |
| `images/` | Dashboard screenshots |

## How to Open

Download the `.twbx` and open it in Tableau Desktop or the free Tableau Public app.

## Author

Jenssen Honore  | [https://www.linkedin.com/in/jenssen-honore-a3b158241/] | 
