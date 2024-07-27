# 🎢 Disneyland Sentiment Analysis with NLP & GCP 🎢

## 📋 Project Overview

Disneyland Park is a place where dreams come true for both children and adults. This project aims to analyze the sentiment of reviews left by visitors using Natural Language Processing (NLP) techniques on Google Cloud Platform (GCP). The analysis helps understand visitors' experiences and emotions. This README will guide you through the steps taken and highlight the ML and DS skills used, as well as mention equivalent services from Azure and AWS.

## 🚀 Activities Performed

### 1. Import Data 📥
#### 1.1 Set Up MySQL Database
- Configured MySQL database to store and manage the review data.

#### 1.2 Import Dataset
- Imported the dataset into MySQL for processing.

#### 1.3 Check for Null Values
- Ensured data quality by checking and handling null values.

### 2. Feature Engineering 🛠️
#### 2.1 Extract Time-Series Features
- Derived time-based features from the review data.

### 3. Exploratory Data Analysis (EDA) 📊
#### 3.1 Data Analysis & Visualizations
- Conducted initial data analysis and created visualizations to understand the raw dataset.

### 4. NLP Sentiment Analysis 🧠💬
#### 4.1 Sentiment Analysis of Reviews
- Calculated sentiment polarity and subjectivity for each review.
- Extracted additional features such as review length.
- Removed stop words for better analysis.
- Exported and saved results to MySQL.

### 5. Performance Enrichment Data Analysis 🚀
#### 5.1 Top 10 Per Branch Analysis
- Analyzed and visualized top reviews per Disneyland branch using various metrics.

### 6. Data Analysis & Visualizations 📈
- Created detailed visualizations using Seaborn and Power BI.

### 6.1 Rates Per Year
- Visualized review ratings over the years.

#### 6.2 Rates Per Branch
- Compared review ratings across different Disneyland branches.

#### 6.3 NLP Sentiment Analysis Per Branch
- Analyzed sentiment distribution for each branch.

#### 6.4 Sentiment Percentage Per Branch
- Visualized the percentage of positive and negative sentiments for each branch.

#### 6.5 Overall Sentiment in Reviews
- Generated word clouds to visualize frequently mentioned positive and negative words.

## 🌐 Cloud Services Comparison

### Google Cloud Platform (GCP)
- **Natural Language API**: Performs sentiment analysis and extracts entities from text.
- **Cloud Storage**: Stores large datasets and files.
- **BigQuery**: Analyzes large datasets with SQL.

### Amazon Web Services (AWS)
- **Comprehend**: Performs sentiment analysis and entity recognition.
- **S3 (Simple Storage Service)**: Stores large datasets and files.
- **Redshift**: Analyzes large datasets with SQL.

### Microsoft Azure
- **Text Analytics**: Performs sentiment analysis and entity recognition.
- **Blob Storage**: Stores large datasets and files.
- **Synapse Analytics**: Analyzes large datasets with SQL.

## 🏢 Use Cases for Businesses

### Customer Experience Management 🏪
- **Sentiment Analysis**: Understand customer emotions and feedback to improve service.
- **Review Monitoring**: Track reviews in real-time to address issues promptly.

### Marketing & Branding 📣
- **Campaign Analysis**: Measure the impact of marketing campaigns through sentiment analysis.
- **Brand Sentiment**: Monitor brand perception and sentiment over time.

### Product Development 🛠️
- **Feature Feedback**: Analyze reviews to gather feedback on specific features.
- **Product Improvement**: Use sentiment analysis to identify areas for product enhancement.

## 🌟 Benefits for Managers

### Enhanced Decision Making
- Data-driven insights from sentiment analysis help in making informed business decisions.

### Improved Customer Experience
- Understanding customer sentiment and feedback leads to better service and product improvements.

### Efficiency & Automation
- Automating sentiment analysis and data visualization saves time and resources, allowing teams to focus on strategic tasks.
