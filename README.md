# Tourist Activity and Taxi Trajectories Dataset

## Overview
This repository contains three datasets related to tourist activities and taxi trajectories in Bangkok, Thailand. The data were collected during the **Songkran Festival (April 11–17, 2019)** and anonymized for privacy.

## Dataset Descriptions

### 1. Tourist Trajectories Extracted from Taxi GPS Data
**Abstract:**  
This dataset contains tourist trajectories within Bangkok, extracted from taxi GPS data.

**Fields:**
- `Vehicle ID`: Unique vehicle identifier
- `lat / lon`: GPS location (up to 5 decimal places)
- `date_time`: GPS timestamp (GMT+7)
- `category`: Place category (origin/destination)
- `distance`: Travel distance (km)
- `time_used`: Travel time
- `tourist_type`: Type of tourist based on expenses
- `trajectory_type`: Type of trajectory based on activity

---

### 2. Segmented Taxi Trajectories
**Abstract:**  
This dataset contains segmented taxi trips with passenger status.

**Fields:**
- `Vehicle ID`: Unique vehicle identifier
- `lat / lon`: GPS coordinates
- `timestamp`: Timestamp (GMT+7)
- `speed`: Speed in km/h
- `heading`: Vehicle direction (0-360 degrees)
- `for_hire_light`: Taxi availability (1 = available, 0 = occupied)
- `trip_point`: Start/end trip label
- `trajectory_id`: Unique trajectory identifier

---

### 3. Anonymous Tourist Activity Dataset from Twitter
**Abstract:**  
An anonymized dataset of Twitter posts related to tourist activities in **Bangkok, Thailand (April 5–24, 2019).**  

**Fields:**
- `anonymous_id`: Unique anonymized identifier
- `datetime`: Timestamp of activity (YYYY-MM-DD HH:00 UTC)
- `user_country`: Country where activity occurred
- `NER`: Named entities extracted from tweets (places, events)
- `district`: Administrative district
- `period`: Time relative to Songkran (Before, During, After)
- `Activity`: Type of activity (e.g., FoodAndDrink, Nightclub/bar, Spa)


