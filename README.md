# Car Brands Analysis Project

This project analyzes consumer perceptions of car brands using textual data from online comments. The goal is to uncover meaningful insights into brand associations, attribute preferences, and aspirational appeal. By examining brand mentions, attribute co-occurrences, and sentiment, this analysis helps us understand consumer attitudes toward top car brands and informs business strategies.

---

## Steps in the Analysis

### 1. Data Preprocessing
- Loaded and cleaned the dataset containing comments about various car brands.
- Tokenized and lemmatized the text data to standardize word forms and improve analysis accuracy.
- Extracted mentions of car brands from the text using predefined brand lists.

### 2. Attribute Categorization
- Created a mapping of car-related words (e.g., "speed," "design") to broader attribute categories such as performance, design, comfort, safety, and technology.
- Grouped these attributes to facilitate an aggregated analysis of brand perceptions.

### 3. Attribute-Brand Co-occurrence Matrix
- Counted the number of times each attribute category was mentioned in association with specific brands.
- Created a matrix showing how frequently each brand is associated with various attributes.

### 4. Lift Analysis
- Calculated lift as a measure of association between car brands and attributes.
- Lift values helped identify which attributes were most strongly linked to specific brands beyond random chance.

### 5. Aspirational Analysis
- Identified keywords (e.g., "want," "buy," "own") indicating a desire to purchase or own a car.
- Measured aspirational mentions for the top 5 most frequently mentioned brands to determine which brand consumers most want to own.

### 6. Visualization
- Used heatmaps to visualize the lift values between car brands and attributes, highlighting strong associations and clusters.

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
