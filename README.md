# Gradio_dashboard
Business Context
ChicStyle — a growing fashion retail platform — experiences massive spikes in customer activity during festive seasons and holiday sales. As people buy clothing and accessories for celebrations, the volume of incoming reviews increases drastically. These reviews pour in every hour, ranging from positive praise to urgent complaints about fit, delivery delays, product defects, or sizing issues.

During such high-pressure periods, even a slight delay in reading or responding to customer feedback can have serious consequences. If the retail team fails to take quick action, customers may feel ignored during an emotionally signifi cant time (festive purchases), leading to frustration, spoiled shopping experiences, and ultimately reduced trust in the brand. This not only results in immediate business loss but also impacts repeat purchases and long-term loyalty.

Retailers need a smart feedback analysis system that can automatically process large volumes of real-time customer reviews, accurately detect sentiment (positive, negative, neutral), identify which product or service the feedback is about, and highlight urgent or high-impact issues.

Traditional NLP models often struggle with this because they depend on fixed rules and limited training data. They can’t easily understand complex or mixed feedback. For example, in the review “The fit is great but the color was not as per the product image,” older systems may give only one sentiment, either positive or negative, missing that the review talks positively about the fit but negatively about the color. Proprietary content.

Generative AI models are much better at this. They can understand the full meaning of a sentence, separate opinions about diff erent products, and catch mixed emotions. This helps retailers get more accurate insights and respond to customer problems faster. Objective:

To avoid customer dissatisfaction and protect brand reputation during peak sales periods, ChicStyle needs a system that can process thousands of reviews instantly, accurately, and with business context.

The system should:

Analyze customer sentiment in real time.
Detect which product/service the review refers to.
Detect urgent issues.
Generate personalized responses.
Create actionable reports for retail teams.

### **Objective**

Build a Generative AI feedback system that uses prompt engineering (Zero-Shot, Few-Shot, and Chain-of-Thought prompting) to:

- Analyze and categorize sentiment in real time.(Positive, Neutral, Negative)

- Detect which product or service each feedback refers to (Size/Fit, Color, Delivery, Fabric Quality, Product Defect, Pricing, Customer Service, Product Design.)

- Summarize insights by product category and urgency level. (High, Medium, Low)

- Automatically send short, personalized messages to customers based on sentiment—thanking them for positive feedback, acknowledging neutral comments, and apologizing for negative ones while informing them that a team member will reach out soon.

- Generate short, actionable reports for retail teams.

This intelligent system will help retailers take quick action on customer issues, improve product quality faster, and enhance customer satisfaction — turning massive unstructured feedback into meaningful, real-time business intelligence.

### **Data Description**

The data contains the different data related to a order review by the customer. The detailed data dictionary is given below.

### **Dataset Used for the Notebook**

This analysis uses the "Women's E-Commerce Clothing Reviews" dataset. The key columns for the analysis are:

- Clothing.ID: A unique ID for each piece of clothing.

- Age: The age of the reviewer (Positive Integer).

- Title: The title of the review (String).

- Review.Text: The main body of the customer's review text (String).

-  Rating: The product score given by the customer, from 1 (Worst) to 5 (Best) (Positive Ordinal Integer).

- Recommended.IND: A binary variable indicating if the customer recommends the product (1 for recommended, 0 for not recommended).
  - 1 for recommended.
  - 0 for not recommended.

- Positive.Feedback.Count: The number of other customers who found the review helpful (Positive Integer).

- Division.Name: The high-level division of the product (Categorical).

- Department.Name: The specifi c department of the product (Categorical).
Describe dataset used for this project.

## Problem Definition

. Retailers need a smart feedback analysis system that can automatically process large volumes of
real-time customer reviews, accurately detect sentiment (positive, negative, neutral), identify which
product or service the feedback is about, and highlight urgent or high-impact issues

. Traditional NLP models often struggle with this because they depend on fixed rules and limited
training data. They can't easily understand complex or mixed feedback. For example, in the review
"The fit is great but the color was not as per the product image," older systems may give only one
sentiment, either positive or negative, missing that the review talks positively about the fit but
negatively about the color.

. Generative Al models are much better at this. They can understand the full meaning of a sentence,
separate opinions about different products, and catch mixed emotions. This helps retailers get more
accurate insights and respond to customer problems faster.

## Overview

This project analyzes customer reviews using AI and displays real-time insights through an interactive Gradio dashboard.

## Features

- Customer sentiment analysis
- AI-generated insights
- Real-time dashboard
- Interactive filtering
- CSV upload support
- Data visualization

## Technologies Used

- Python
- Gradio
- Google Gemini AI
- Pandas
- Plotly

## Project Structure

review_analyzer_updated.py
Clean_sample_50.csv
requirements.txt

## How to Run

```bash
pip install -r requirements.txt
python review_analyzer_updated.py
```

## Future Improvements

- Gradio Integration
- SQL Database
- Azure Deployment
- Real-time API

## Author

Indu K Saini
Business Analyst | Data Analytics | AI
