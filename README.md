
# 📊 Flipkart Mobiles Data Analysis

This project analyses mobile phone data from Flipkart using SQL to uncover patterns in pricing, discounts, ratings, and reviews.

---

## 📝 Project Overview

* **Database**: `flipkarts`
* **Table**: `mobiles` (data imported from `flipkart_mobiles.csv`)
* **Goal**: Perform exploratory analysis on Flipkart mobile listings to extract actionable insights such as price range distribution, brand-wise performance, and discounts.

---

## ⚙️ How It Works

1. A database named **flipkarts** is created.
2. The dataset **flipkart\_mobiles.csv** is uploaded into a table named **mobiles**.
3. SQL queries are run to:

   * Segment mobiles into different price ranges.
   * Find brands offering the highest discounts.
   * Identify top brands by average ratings.
   * Identify brands with the highest number of reviews.
   * Highlight products with high ratings and big discounts.
   * Calculate average rating and total reviews per brand.
   * List top discounted products and extract unique brand names.

---

## 🔍 Key Insights

* **Price Segmentation**: Mobiles are grouped into different price ranges (Below 10k, 10–20k, 20–40k, Above 40k).
* **Discount Analysis**: Identify brands and products with the highest discounts.
* **Ratings & Reviews**: Evaluate brands based on average ratings and total number of reviews.
* **Top Products**: Highlight mobiles with ratings greater than 4.5 or discounts over 40%.
* **Brand Diversity**: Extract unique brand names from the dataset.

---

## 📂 Dataset

* **Name**: `flipkart_mobiles.csv`
* **Attributes**: Brand, MRP, MSP, Ratings, Number of Reviews, Discount, etc.

---

## 🛠️ Tech Stack

* SQL (MySQL / MariaDB)
* CSV Dataset

---

## 🚀 Outcomes

* Clear understanding of Flipkart’s mobile phone pricing trends.
* Data-driven insights on customer reviews and ratings by brand.
* Identification of top-performing brands and products.

---

## 📜 License

This project is open-source and free to use for learning and analysis purposes.

