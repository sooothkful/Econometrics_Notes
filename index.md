

# THE SCOPE OF ECONOMETRICS

**Econometrics is based upon the development of statistical methods for estimating economic relationships, testing economic theories, and evaluating/implementing government and business policy. Econometric methods can be used in areas that have nothing to do with macroeconomic forecasting. Still, the most common application of econometris is the forecasting of interest rates, inflation rates and gross domestic product.**

**Nonexperimental Data** - also called observational data or retrospective data

**Experimental Data** - Difficult to collect in social sciences (very expensive)

- Econometrics and mathmatical statistics both focus on multiple regression analysis, but the focus and interpretation in either field can differ drastically



## Emperical Economic Analysis

 - Uses data to test theory or to estimate a relationship
 
 - Requires data
 
 - Steps to performing emperical analysis:
 
   **1. Careful formulation of the question of interest**
      
      In some cases, a formal economic model is constructed (in the case of testing economic theories)
      
      **The basic premise in economic models is utility maximization** - in the case of consumption decisions, utility maximization leads to a let of demand equations
      
      In a demand equation, the quantity demanded of each commodity depends on the price of the goods, price of the substitute/complementary goods, consumer's income and the
      individual's characteristics that affect taste. These equations can form the basis of an econometric analysis of consumer demand.
   
   **2. Form economic model**
 
    - Start with intuition 
    
    - Or start with economic model (a little more informally)
 
   **3. Convert economic model to econometric model**
   
    - An econometric model must take on the form of function f(.) before we can perform an econometric analysis.
    
    - Must deal with variables that can not reasonably be observed.
    
    - We can derive a variable that approximates either the probability
    
    - The ambiguities in the economic model of crime are resolved by creating the following econometric model:
    
        
            crime = β₀ + β₁wageₘ + β₂othinc + β₃freqarr + β₄freqconv + β₅avesen + β₆age + u,
            
            where
            
            crime = some measure of the frequency of criminal activity
            wageₘ = wage that can be earned in legal employment
            othinc = the income from other sources (assets, inheritance, etc.)
            freqarr = frequency of arrest for prior infractions (to approximate the probability of arrest),
            freqconv = frequency of conviction
            avgsen = average sentence length after conviction
            u = unobserved factors
            constants β₀ - β₆ - are the parameters of the model - describe direction and strength of the relationship between crime and the factors used to determine crime
            
   - The variables in the above model are based on economic theory and data considerations.
   
   - Can never eliminate u (unobserved factors) entirely
   
 **4. Deal with the error term (disturbance term) - possibly the most important part of econometric analysis.**
 
 **5. Various hypothesis of interest can be stated in terms of unknown parameters.**
 
 **6. Collect data on relevant variables**
 
 **7. Use econometric methods estimate parameters and formally test hypothesis**
 
 **8. Use model to make predictions**

## The Structure of Economic Data

**The most common types of data structures that are used in applied econometrics are:**
**1. Cross-Sectional Data**
**2. Time Series Data**
**3. Pooled Cross Sections**
**4. Panel Data**

### Cross-Sectional Data

  - Consists of a sample of individuals, households, firms, cities, states or other units, collected at a certain point in time.
  
  - If there is minor variance in the times that the data is collected - it would not matter - data would still be used in a cross-sectional study.
  
  - Data should be collected by **random sampling.**
  
### Time Series Data

  - Consists of observations on a variable or several variables over time.
  
  - Ex: Stock prices, money supply, consumer price index, GDP, annual homicide rates, auto sales figures
  
  - The chronological ordering of time series data can convey important information.
  
  - May be more difficult to analyze than cross-sectional data because economic observations can rarely, if ever, be assumed to be independent across time.
  
  - Most economic and other times series are related and often strongly related to recent histories.
  
  - More needs to be done when dealing with time series data in the formulation of an econometric model.
  
  - **Data Frequency - how often is data collected?**
  
    Stock prices - daily
    
    U.S. money supply - weekly
    
    Inflation - monthly
    
    Unemployment Rates - monthly
    
    GDP - quarterly (every 3 months)
    
    Infant mortality rates - annually
    
  - **Look for patterns/trends**
  
  - Data must be listed in chronological order.
  

## Pooled Cross Sections

   - Pooled cross-sectional studies are often performed to analyze the effect of a new government policy. (Collect data from the years before and after policy was implemented)
   
   - A pooled cross-section combines data from multiple years.
   
   - The purpose of pooling cross sections is sometimes to increase sample size.
   
   - Other times it is used to see how a key relationship has changed over time.
  
## Panel or Longitudinal Data

   - consists of a time series for each cross-sectional member in the data set.
   
   - the key feature of panel data is that the same cross-sectional units are followed over a given time period (like statistics for certain variables for certain states).
   
 ## Ceteris Paribus - "other factors being equal"
 
 - If all other factors are not held fixed, then we cannot know the **causal effect** of a variable.
 
 **Key question in emperical studies is: "Have enough other factors been held fixed to make a case for causality?"
      






# PYTHON & ECONOMETRIC ANALYSIS

 **Important things to consider:**
 
  **Reproducibility** 
  
       - In order for someone to look at our analysis and understand where the results come from we need to use Python scripts.
         
       - Our Python script will contain all the commands for the project from start to finish.
       
       - Use comments.
       
       - Use variable names within functions.
       
                 ex: print(f'some text {variablename}')
                 
                 >>> result1 = 1 + 1
                 >>> print(f'result1: {result1}\n')
                 result1: 2
                 
 **Modules (Functions) **
 
  - Python files that contain functions and variables.
  
  - Python comes with built-in modules.
  
  - Must import modules and same as some alias name.
  
  - After import, modules can be accessed via dot notation.
  
  - Use pip install to install many packages 
  
  - Useful packages:
  
    **wooldridge** - datasets to accompany book
    **numpy** - most fundamental computing package for array computing with Python
    **pandas** - powerful data structures for data analysis, time series, and statistics
    **pandas_datareader** - data readers extracted from the pandas codebase
    **statsmodels** - statistical computations and models for Python
    **matplotlib** - Python plotting package
    **scipy** - Scientific library for Python
    **patsy** - Python package for describing statistical models and building design matrices
    **linearmodels** - Instrumental variable and linear panel models for Python
    
  - Save generated files as text, spreadsheet or Latex files
  
  - File paths:
  
     - import os module
     
     - obtain os module with os.getcwd()
     
     - To change working directory - os.chdir(path)
     
    
    
    
                 
                 
       


##
  
 
  



      


