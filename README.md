

## MOVIE VENTURE ANALYSIS

This project seeks to understand the film industry by analysing the genre trends, ratings and financial returns thereby providing actionable insights for the new business venture. 

## 1. DATA SETS USED 

For this project, we used the following data sets 

1. **IMDB DATA**

    -This database contains 2 datasets that we used for our analysis. 
        -movie_basics which contains information such as titles, production years, genres and runtimes. This dataset was useful in exploring movie characteristics, genres and trends over years. 
        -movie_ratingswhich contains data about ratings and was useful in analysing popualrity of movie_basics

2. **Bom.movie_gross**

    -This dataset was useful in analysing the financial performance of movies across different geographical regions over time.

 
## 2. PROJECT OVERVIEW

Since our company is entering the film production space, this project will leverage on the analysis of current trends and financial perfrmance to determine how and where to invest for maximum profit. 

## 3. GENERAL OBJECTIVE 

The general objetcive is to use data science methodologies to analyse box office perfomance, audience preferences, and financial patterns with the goal of generaing actionable recommendations for our company to invest in.

### KEY OBJECTIVES

1. **Identify genres that perfomr best in terms of cos, revenue, profitability and ratings.**

2. **Determine the optimal release period, casting themes or storytellling elements.**

3. **Recommend high-potential film types for exploration and developement.**

## TOOLS AND TECHNOLOGIES

1. **Python**: Utilized as the core programming language for data analysis and manipulation.

2. **Pandas**: Played a vital role in organizing, cleaning, and handling datasets efficiently.

3. **Matplotlib & Seaborn**: Employed to generate visualizations that reveal data patterns and insights.

4. **Jupyter Notebook**: Used as the interactive platform for performing and documenting the analysis.

## 4. WORKFLOW

### 1. DATA CLEANING 
The initial phase focused on importing and preparing the datasets. This process included:

    -Addressing missing data by removing incomplete records.

    -Ensuring proper formatting of columns, such as standardizing date formats and converting numerical values.
    
    -Eliminating duplicate entries to maintain data accuracy and consistency.

    -Dropping columns that will not be used for analysis.

### 2. DATA ANALYSIS

During this phase, the data was explored to identify patterns. This included:

    -Frequency distributions and the co-occurrence of various genres.

    -Correlation of genres and their release dataset using heatmaps.

    -visualisation of performance metrics such as financials revenue and ratings.


### 3. RETURN ON INVESTMENT (ROI) ANALYSIS

During this phase, analysis was done on the financial performance to identify the following,
 
    -Genres that had the highest average return on investment after considering their production budget.

    -The financial performance of different genres in the domestic and foreign markets. 


## 5. KEY INSIGHTS 

#### 5.1 Genres

1. Overall, mainstream and emotionally resonant genres like *Drama, **Comedy, and **Action* are popular in the movie industry and on demand among the audience. Specialized or genre-specific categories such as *Western, **Musical, and **News* are comparatively rare.

2. Genre combinations having a common occurrence included *Drama + Romance, **Action + Adventure, and **Thriller + Crime. Some genres like **Horror, *Mystery, and **Biography* were most frequently used in focused or specialized narratives.

3. Genres maintained an even spread of releases throughout the year (Ex. *Action, **Comedy, and **Adventure*), others exhibited strong seasonal preferences especially in Autumn and Winter indicating targeted release strategies possibly tied to awards seasons, holidays, or peak box office periods. Specifically 

#### 5.2 Financial performance

1. Average performance metrics across top ten major movie genres indicate that:  

   a). *Adventure* and *Action* dominate as the most expensive genres to produce, with average production costs with relatively high returns.  

   b). *Horror* and *Mystery* emerge as the most financially efficient genres, posting the highest average return on investment (ROI) at 11.71 and 11.24, respectively. These genres are comparatively inexpensive to produce but yield disproportionately high returns, making them highly attractive to studios with limited budgets or those seeking high-margin ventures.  

   c). *Romance* and *Drama* maintain a balance between audience appreciation and profitability, offering moderate ROI and good ratings.  

   d). *Crime* and *Thriller* although reasonably profitable, deliver lower ROI, suggesting they may carry more financial risk unless backed by strong scripts or cast.

2. In the film industry, investments will likely depend on the choice of strategy. Current trends indicate that studios seeking blockbuster success should focus on *Adventure* and *Action. Studios that prefer prioritizing *efficiency and high returns should look to *Horror, **Mystery, or **Romance. Studios aiming for *critical acclaim or awards recognition may find the best value in *Biography* and *Drama*. This table underscores that different genres fulfill different strategic objectives, and aligning production choices with business goals is key to success in the film industry

3. Over the last 15 years, financial trends on revenue, costs and profitability present an upward trend implying market growth for box office movies, especially the foreign markets.

4. Genres with the highest audience ratings do not always generate the highest financial returns, and vice versa. *Horror* and *Mystery* are some  examples of high-ROI, low-to-mid-rating genres.

#### 5.3 Markets

1. Foreign revenue consistently outperforms domestic revenue, highlighting the growing importance of international markets for film profitability. International audiences are a crucial revenue source regardless of genre, and studios might benefit from tailoring content with global appeal.   

    a). Adventure and Action genres generate the highest revenues in both foreign and domestic markets  

    b). Adventure presents a significant margin it's foreign revenue i.e More than double its domestic market  

    c). Comedy, Thriller, and Crime genres also exhibit strong international performance  

#### 5.3 Average Rating

1. Overall average rating patterns show a long-term decline followed by partial recovery and consistency, which may reflect the industry's adaptation to audience preferences, critical standards, and evolving storytelling approaches

2. Voting behavior has evolved, first with steady growth, then with digital-era acceleration, and subsequently a decline possibly due to a larger volume of films being released (diluting votes), or newer releases having had less time to accumulate votes.

3. *Biography* has the highest-rated genre, followed closely by *Drama* and *Adventure*, indicating these genres tend to deliver strong storytelling and quality content appreciated by viewers

#### 5.4 Other performance measures

1. *Average Runtime* The industry has settled on a more standardized length for mainstream films. This could be influenced by streaming trends, theatrical scheduling preferences, or evolving attention spans of audiences.

2. Standout production houses that balance both *financial performance* and *critical acclaim* based on ROI and average rating by genres were  

   a). *UTV* was financially efficient and also creatively successful in the production of *Action* and *Biography* genres.  

   b). *GrtIndia* was best placed in the production of high-rated *Action* and *Drama* genres    

   c). *Orch.* produced top-rated films across several genres including *Adventure, Comedy, and Drama*  

   d). *BSC* maintains high ratings in *Action* and *Drama*  

   e). *Studio 8* and *SPC* are more prominent in the average rating across genres like *Horror, **Mystery, and **Thriller*, they are not top ROI earners—indicating that while their films are critically appreciated, they may not be as financially optimized

## 6. RECOMMENDATIONS 

#### 6.1 Investment Portfolio 

1. High budget: The data shows Action and Adventure titles cost the most but also pull in the widest audiences and sells best overseas. They are best launched in the spring or summer, when blockbuster demand is highest and foreign box-office potential is strongest. Success strategy: pack theaters worldwide and hit the release window that maximises revenue.  

2. Mid budget: Conclusions point out that Drama mixed with Romanc or Crime paired with Thriller delivers a healthy balance of good ratings, decent ROI, and festival attention without runaway budgets. Success strategy - Target festival buzz and good reviews for free marketing, helping these films earn steadily year-round and boosting the studio’s reputation.  

3. Low budget: Horror and Mystery/Thriller are inexpensive to make yet top the ROI tables, according to the study. By capping budgets below $10 million and timing releases near Halloween or other proven windows, can limit risk while giving a chance at the next breakout hit.

## 7. CONCLUSION
This insights will position the company to move into the film industry and produce work that is competitive and profitable.

## 8. CONTRIBUTORS

1. Joackim Kisienya
2. Eric Metobo
3. Hezron Rumenya
4. Joy Sila
5. Lynn Kyalo
6. Newton Njeri
