# Infosys Employee Sentiment Analysis

## 📊 Project Overview
This project analyzes employee reviews of Infosys to understand sentiment patterns, key satisfaction drivers, and common concerns. The analysis includes both quantitative metrics (ratings) and qualitative insights from employee feedback.

## 📁 Dataset
- **File**: `infosys_data.csv`
- **Records**: 300 employee reviews
- **Timeframe**: October 2024
- **Key Columns**:
  - `rating`: Employee rating (1-5 scale)
  - `title`: Review title
  - `location`: Infosys location in India 
  - `role`: Job position
  - `date`: Review date
  - `pros`: Positive aspects mentioned
  - `cons`: Negative aspects mentioned

## 🔍 Key Findings

### Overall Ratings
- **Average Rating**: 3.6/5
- **Rating Distribution**:
  - ⭐⭐⭐⭐ (4.0): 50% of reviews
  - ⭐⭐⭐ (3.0): 30% of reviews
  - ⭐⭐⭐⭐⭐ (5.0): 10% of reviews
  - ⭐⭐ (2.0): 10% of reviews

### Sentiment Analysis
- **Pros Sentiment**: Highly positive (0.636 polarity)
  - 90% positive sentiment
  - 10% neutral sentiment
- **Cons Sentiment**: Slightly negative (-0.154 polarity)
  - 60% neutral sentiment
  - 40% negative sentiment
- **Overall Correlation**: Strong positive correlation (0.803) between numerical ratings and sentiment scores

### Role-Based Satisfaction
**Top Roles by Satisfaction:**
1. Technology Analyst: 4.5/5
2. QA Engineer: 4.0/5
3. Systems Engineer: 4.0/5
4. Technical Lead: 4.0/5
5. Anonymous Employee: 4.0/5

**Lower Satisfaction Roles:**
- Senior Software Engineer: 2.0/5
- Associate Business Analyst: 3.0/5
- Technology Lead (US): 3.0/5

### Common Concerns Analysis
**Most Frequently Mentioned Issues:**
1. **Salary & Compensation**: 150 mentions (50% of reviews)
2. **Career Growth**: 60 mentions (20% of reviews)
3. **Management Issues**: 60 mentions (20% of reviews)
4. **Work-Life Balance**: 30 mentions (10% of reviews)

### Tenure Analysis
Employee tenure was categorized as:
- Less than 1 year
- 1-3 years
- 3-8 years
- 8+ years

## 🛠️ Technical Implementation

### Libraries Used
- `pandas` - Data manipulation
- `numpy` - Numerical operations
- `matplotlib` & `seaborn` - Data visualization
- `scikit-learn` - Topic modeling (LDA)
- `textblob` - Sentiment analysis
- `wordcloud` - Text visualization

### Analysis Methods
1. **Descriptive Statistics**: Rating distributions and averages
2. **Sentiment Analysis**: Polarity and subjectivity scoring
3. **Topic Modeling**: LDA for identifying common themes in pros/cons
4. **Role-based Analysis**: Satisfaction by job position
5. **Text Mining**: Keyword frequency analysis for common issues
6. **Time Series**: Monthly sentiment trends

## 📈 Visualizations
The analysis includes:
- Histograms of sentiment distribution
  <img width="802" height="497" alt="image" src="https://github.com/user-attachments/assets/781d7674-cad6-4d51-8eac-6e37d61c488c" />
  
- Pie charts for sentiment categories
  <img width="653" height="412" alt="image" src="https://github.com/user-attachments/assets/3b478d97-de9e-4c9e-a658-f1de8ff664f9" />

  <img width="467" height="459" alt="image" src="https://github.com/user-attachments/assets/88b8164b-de1e-4cfd-953f-4472356d55db" />

  
- Scatter plots showing rating vs sentiment correlation
  <img width="840" height="514" alt="image" src="https://github.com/user-attachments/assets/2eca687f-edeb-4861-ab62-7fea6f033a02" />
  
- Role-based satisfaction comparisons
  <img width="799" height="588" alt="image" src="https://github.com/user-attachments/assets/fc02d631-9956-4be6-aa8b-908ab594be54" />

- Sentiment Analysis by Tenure
  <img width="795" height="542" alt="image" src="https://github.com/user-attachments/assets/437dfc44-e46e-4d5e-870d-b303cacd37ff" />


## 💡 Business Insights

### Strengths
- **Infrastructure**: Consistently praised
- **Training Programs**: Well-regarded by employees
- **Job Security**: Positive mention across reviews
- **Policy Structure**: Appreciated by technology roles

### Areas for Improvement
1. **Compensation**: Most significant concern across all roles
2. **Career Growth**: Limited advancement opportunities
3. **Management**: Regional bias and poor manager support mentioned
4. **HR Responsiveness**: Communication issues highlighted

## 🎯 Recommendations
1. **Review Compensation Structure**: Address salary concerns, particularly for senior roles
2. **Enhance Career Development**: Create clearer growth paths and promotion opportunities
3. **Improve Management Training**: Focus on reducing regional bias and improving leadership quality
4. **Strengthen HR Support**: Enhance responsiveness and employee support systems
5. **Role-specific Initiatives**: Tailor improvements based on role-specific satisfaction levels

## 📋 Next Steps
Potential enhancements for deeper analysis:
- Comparative analysis with other IT companies
- Longitudinal tracking of sentiment changes
- Department-specific deep dives
- Exit interview correlation analysis

---

*Note: This analysis is based on 300 employee reviews from October 2024 and provides a snapshot of employee sentiment at that time.*
