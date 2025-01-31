# Car Brands Analysis Project

This project analyzes consumer perceptions of car brands using textual data from online comments. The goal is to uncover meaningful insights into brand associations, attribute preferences, and aspirational appeal. By examining brand mentions, attribute co-occurrences, and sentiment, this analysis helps us understand consumer attitudes toward top car brands and informs business strategies.

## Steps in the Analysis

### 1. Data Preprocessing

- Loaded and cleaned the dataset containing user comments about various car brands.
- Tokenized and lemmatized the text data to ensure consistency and accuracy in word representation.
- Extracted mentions of car brands using a predefined brand list to analyze brand-specific insights.

### 2. Brand Mention Frequency

- Which car brands are most frequently discussed, and which ones are top of mind for users?
- Identified the most mentioned brands to determine user recall and interest levels.
- Counted the occurrences of each car brand in the dataset and used a word cloud to better visualize it.
![image](https://github.com/user-attachments/assets/326614e2-795e-4073-a7c7-c1b40fe080c2)

### 3. Brand Comparisons and Competitive Landscape

- Are certain brands frequently mentioned together, indicating comparisons or competition?
- Identified whether brands are substitutes, competitors, or belong to the same market segment based on user discussions.
- Analyzed the Lift Matrix Heatmap of Top 10 Brands to understand co-occurrence patterns.
![image](https://github.com/user-attachments/assets/1e34e70c-b54d-42a2-8ff7-6deae327a0cc)


### 4. Multi-Dimensional Scaling (MDS) Plot

- How are car brands perceived in relation to each other?
- Provided insights into brand positioning and relative similarity, helping identify clusters of brands commonly mentioned together.
- Applied **Multi-Dimensional Scaling (MDS)** to visualize brand relationships based on co-occurrence patterns.
![image](https://github.com/user-attachments/assets/c27cbde3-5669-4836-8ba1-44711783c9dc)

### 5. Attribute Categorization

- How do users describe different car brands? What aspects of cars matter most to them?
- Created a mapping of car-related words (e.g., "speed," "design") to broader attribute categories such as performance, design, comfort, safety, and technology.

### 4. Attribute-Brand Co-occurrence Matrix

-- Which car attributes are most distinctive for the top brands?
- Counted the number of times each attribute category was mentioned alongside specific brands.
- Identified the strongest associations between specific attributes and brands, revealing what stands out for each major brand.
- Generated a heatmap to visualize the lift values between these brands and car attributes.
![image](https://github.com/user-attachments/assets/96eacce5-3aea-48ea-9a1f-17b6a1db78cc)

### 6. Aspirational Analysis

- Which brands do consumers express a strong desire to own?
- Identified aspirational keywords (e.g., "want," "buy," "own") to measure user intent.
- Analyzed how often these aspirational terms appeared in connection with the top 5 most mentioned brands and which brand has the highest level of consumer desire.

---

## Insights and Business Implications

### General Insights
- **Brand Differentiation**:  
  BMW stands out as the most aspirational brand, with strong associations across all major attributes, including performance, design, comfort, build quality, and handling.

- **Aspirational Appeal**:  
  BMW had nearly four times more mentions of intent to buy than any other brand, reinforcing its positioning as a highly desirable luxury brand.

- **Attribute Specialization**:
  - **Honda**: Strongly associated with safety, indicating a focus on reliability and family-friendly features.
  - **Audi**: Leads in design and handling, appealing to consumers seeking a balance of aesthetics and driving dynamics.
  - **Acura**: Performs well in safety and technology, suggesting a focus on innovation and consumer trust.
  - **Infiniti**: Shows strong associations with comfort and technology, positioning itself as a luxurious yet accessible brand.

---

### Recommendations
- **BMW**:  
  Leverage its aspirational status with targeted promotions for entry-level models and campaigns emphasizing its dominance in performance and design.

- **Audi**:  
  Invest in marketing campaigns highlighting its superior design and handling, while improving its technology offerings to remain competitive.

- **Honda**:  
  Focus on its safety leadership to attract family-oriented buyers while exploring opportunities to improve performance and build quality.

- **Acura**:  
  Strengthen its position in fuel-efficiency technologies by investing in hybrid or electric powertrains to appeal to environmentally conscious consumers.

- **Infiniti**:  
  Build on its strengths in comfort and technology to position itself as a luxurious yet tech-savvy option.

---

## Tools and Libraries Used

- **Python**: Primary programming language for the analysis.
- **NLTK**: Used for text tokenization, lemmatization, and POS tagging.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib/Seaborn**: Visualization of results, including heatmaps and trends.
- **NumPy**: Numerical computations and array operations.
- **Scikit-learn**: Used for dimensionality reduction (MDS) and clustering to identify brand relationships.
- **NetworkX**: Analyzed and visualized brand-attribute co-occurrence networks.
- **SciPy**: Statistical calculations for advanced association measures like lift.
- **Jupyter Notebook**: Interactive environment for running and documenting the analysis.
