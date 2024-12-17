# **Airbnb : Basic Analysis on Prices**

### **Project Overview**  
This project aims to perform a basic analysis of Airbnb listings in India. We will clean and transform the dataset, and then conduct hypothesis testing to understand the factors influencing rental prices. The analysis will focus on the following key variables:
- **Guest Capacity** (Number of Guests)
- **Room Type**
- **Guest Ratings (Stars)**

Through hypothesis testing and data visualization, we will explore how these factors influence **rental prices** for Airbnb listings in India.

---

## **Data Cleaning and Transformation**  
Before diving into the analysis, we first clean and transform the dataset by:  
- **Renaming columns** for clarity:  
   - `location/lat` → **latitude**  
   - `location/lng` → **longitude**  
   - `numberOfGuests` → **guest_no**  
   - `roomType` → **room_type**  
- **Dropping unnecessary columns** such as `isHostedBySuperhost`.  
- **Handling missing values** in the **stars** column.

---

## **Research Questions**  

The primary goal of this analysis is to answer the following research questions:

1. **Does the guest capacity (number of guests) influence the rental price?**
2. **Does room type affect the rental price?**
3. **Is there any correlation between guest ratings (stars) and rental price?**

These questions will guide our hypothesis testing and exploratory data analysis.

---

## **Hypothesis Testing**

We will perform the following hypothesis tests to answer the research questions:

### **Hypothesis 1: Listings with Higher Guest Capacity Have Higher Prices**

We will test if **listings with more guests** tend to have **higher prices**.

- **Null Hypothesis (H0)**: There is no significant difference in prices based on guest capacity.  
- **Alternative Hypothesis (H1)**: Listings with higher guest capacity have higher prices.

---

### **Hypothesis 2: Different Room Types Have Different Average Prices**

We will test if the rental price differs significantly across **room types**.

- **Null Hypothesis (H0)**: All room types have the same average rental price.  
- **Alternative Hypothesis (H1)**: Different room types have different average rental prices.

---

### **Hypothesis 3: There Is a Positive Correlation Between Guest Ratings and Rental Price**

We will test if **higher guest ratings** are associated with **higher rental prices**.

- **Null Hypothesis (H0)**: There is no correlation between guest ratings and rental price.  
- **Alternative Hypothesis (H1)**: There is a positive correlation between guest ratings and rental price.

---

## **Tools and Technologies**  
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook**: For analysis and documentation
