# Dataset Information

## 📌 Overview
This dataset represents **digital advertising and social media campaign data** used for analysis and visualization in a Power BI dashboard.  
It simulates real-world marketing data, including campaigns, ads, users, and user interaction events.

The dataset is suitable for:
- Marketing analytics
- Social media performance analysis
- User engagement analysis
- Power BI dashboard projects

---

## 📂 Dataset Structure
The dataset consists of **four CSV files**:

campaigns.csv
ads.csv
users.csv
ad_events.csv


---

## 📁 File Descriptions

### 1️⃣ `campaigns.csv`
Contains high-level information about advertising campaigns.

**Columns:**
- `campaign_id` – Unique identifier for each campaign  
- `name` – Campaign name  
- `start_date` – Campaign start date  
- `end_date` – Campaign end date  
- `duration_days` – Total campaign duration in days  
- `total_budget` – Total budget allocated to the campaign  

---

### 2️⃣ `ads.csv`
Contains details about individual advertisements linked to campaigns.

**Columns:**
- `ad_id` – Unique identifier for each ad  
- `campaign_id` – Campaign ID the ad belongs to  
- `ad_platform` – Platform where the ad is displayed (e.g., Facebook, Instagram)  
- `ad_type` – Type of advertisement (image, video, carousel, etc.)  
- `target_gender` – Targeted gender group  
- `target_age_group` – Targeted age group  
- `target_interests` – Target audience interests  

---

### 3️⃣ `users.csv`
Contains demographic and interest data of users interacting with ads.

**Columns:**
- `user_id` – Unique identifier for each user  
- `user_gender` – Gender of the user  
- `user_age` – Age of the user  
- `age_group` – Age group classification  
- `country` – Country of the user  
- `location` – City or region  
- `interests` – User interest categories  

---

### 4️⃣ `ad_events.csv`
Logs user interactions with advertisements.

**Columns:**
- `event_id` – Unique identifier for each event  
- `ad_id` – ID of the ad involved  
- `user_id` – ID of the user who interacted  
- `timestamp` – Date and time of the interaction  
- `day_of_week` – Day when the event occurred  
- `time_of_day` – Time category (morning, afternoon, evening, night)  
- `event_type` – Type of interaction (view, click, like, share, etc.)  

---

## 🔗 Relationships Between Tables
- `campaigns.csv` → `ads.csv` via `campaign_id`
- `ads.csv` → `ad_events.csv` via `ad_id`
- `users.csv` → `ad_events.csv` via `user_id`

These relationships enable **star-schema-style modeling** in Power BI.

---




