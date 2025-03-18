# Business Understanding Document

## 1. What is the Goal?

The goal is to help a wealthy investor decide if they should buy **TellCo**, a mobile service provider in the Republic of Pefkakia. The investor wants to know:

- Is TellCo a good investment?
- How can TellCo make more money?

To do this, we will analyze TellCo’s data to understand:

- **User Overview**: Who are the customers, and what devices do they use?
- **User Engagement**: How are customers using TellCo’s services?
- **User Experience**: Are customers happy with the network and services?
- **User Satisfaction**: How satisfied are customers overall?

---

## 2. What is the Problem?

TellCo’s current owners have not used their data to understand their customers or improve their business. This means:

- They don’t know which customers are the most profitable.
- They don’t know why some customers leave (this is called **churn**).
- They might be missing opportunities to grow.

---

## 3. What Data Do We Have?

TellCo has shared their data, which includes information about:

- **Customers**: Their phone numbers, devices, and usage.
- **Network Usage**: How much data customers use, how long they use it, and how fast the network is.
- **Applications**: How much data customers use for apps like YouTube, Netflix, Google, and Gaming.

Here’s a breakdown of the data fields:

- **Bearer ID**: A unique ID for each data session.
- **Duration**: How long each session lasts.
- **Start/End Time**: When each session starts and ends.
- **Customer Info**: Phone number, device type, and location.
- **Network Performance**: Speed, delays, and retransmissions.
- **App Usage**: Data used for apps like YouTube, Netflix, and Gaming.

---

## 4. How Can Data Help?

We can use the data to:

1. **Understand Customers**:
   - Find out which devices customers use the most.
   - See which apps customers use the most.
2. **Improve Engagement**:
   - Identify the most active customers.
   - Group customers based on how much they use the network.
3. **Improve Experience**:
   - Check if the network is fast and reliable.
   - See if certain devices cause problems.
4. **Measure Satisfaction**:
   - Combine engagement and experience to see how happy customers are.
   - Predict which customers might leave.

---

## 5. What Are the Tasks?

### **Task 1: User Overview Analysis**

- Find out the top 10 most used phones.
- Identify the top 3 phone manufacturers.
- Analyze app usage (YouTube, Netflix, Gaming, etc.).
- Clean the data by fixing missing values and outliers.

### **Task 2: User Engagement Analysis**

- Track how often customers use the network.
- Measure how long they stay online.
- Group customers into 3 engagement levels (low, medium, high).
- Find the top 10 most engaged customers.

### **Task 3: User Experience Analysis**

- Check network performance (speed, delays, retransmissions).
- Analyze how different devices affect the experience.
- Group customers into 3 experience levels (bad, okay, good).

### **Task 4: User Satisfaction Analysis**

- Combine engagement and experience to measure satisfaction.
- Predict which customers are most satisfied.
- Build a model to track satisfaction over time.

---

## 6. Additional Analysis Ideas

Here are some extra things we can do with the data:

1. **Churn Prediction**:
   - Predict which customers are likely to leave TellCo.
   - Find out why they might leave (e.g., bad network, high costs).
2. **Revenue Analysis**:
   - Find out which customers bring in the most money.
   - Suggest new pricing plans to increase revenue.
3. **Network Optimization**:
   - Identify areas where the network is slow or unreliable.
   - Suggest improvements to make the network faster.
4. **App-Specific Insights**:
   - Find out which apps use the most data.
   - Suggest partnerships with popular apps (e.g., Netflix, YouTube).
5. **Geographical Analysis**:
   - Find out where most customers are located.
   - Suggest areas where TellCo can expand.

---

## 7. Limitations and Assumptions

### **Limitations**

1. **Only One Month of Data**:
   - We only have data for one month, so we can’t see long-term trends.
   - Seasonal changes (e.g., holidays) might affect the results.
2. **Missing Data**:
   - Some fields might have missing or incorrect values.
   - We’ll need to clean the data before analyzing it.
3. **No Customer Feedback**:
   - We don’t have direct feedback from customers about their experience.
   - We’ll have to rely on network and usage data to measure satisfaction.
4. **Limited Geographical Data**:
   - We don’t have detailed location data for all customers.
   - This might make it hard to analyze regional trends.

### **Assumptions**

1. **Data is Representative**:
   - We assume the data we have is a good representation of TellCo’s customers.
2. **Network Performance Affects Satisfaction**:
   - We assume that faster networks and fewer delays make customers happier.
3. **Engagement Equals Profitability**:
   - We assume that customers who use the network more are more profitable.
4. **One Month is Enough**:
   - We assume that one month of data is enough to make useful recommendations.

---

## 8. What Are the Next Steps?

1. **Explore the Data**: Look at the data to understand what’s in it.
2. **Clean the Data**: Fix any missing or messy parts.
3. **Analyze the Data**: Find patterns and insights.
4. **Build a Dashboard**: Create a tool to show the results.
5. **Write a Report**: Explain our findings and recommendations.

---

### Example for TellCo

- **Goal**: Decide if TellCo is worth buying and how to make it more profitable.
- **Problem**: TellCo doesn’t know which customers or services are the most profitable.
- **Data**: Customer info, usage data, network performance, app usage.
- **Solution**: Analyze the data to find profitable customers, improve engagement, and measure satisfaction.
- **Success**: The investor buys TellCo and increases profits by 25% in 6 months.
