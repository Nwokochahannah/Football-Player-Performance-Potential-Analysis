# Football-Player-Performance-Potential-Analysis
#### Project Goals and Objectives

Football Player Performance & Potential Analysis is a project to analyse the performance of football players from the top 5 leagues in Europe in the 2023/2024 season. The goal of the project is to evaluate how football players in the these leagues performed in the 2022/2023 season, focusing on key metrics such as goals, assists, defensive actions, and other relevant performance indicators and to compare real-life player statistics with their potential ratings provided by EA Sports to identify:
- **Overperformers**: Players whose real-life stats exceed their EA ratings.
- **Underperformers**: Players with high EA potential but lower-than-expected real-life performance.

#### Dataset Descriptions

##### 1. Top 5 Leagues Dataset
This dataset contains performance statistics for players in the top 5 European football leagues (Premier League, La Liga, Serie A, Bundesliga, Ligue 1) during the 2023/2024 season. It includes detailed player statistics such as goals, assists, defensive actions, and passing accuracy. Key features in the dataset include:
- **Player Name**: The full name of the player.
- **Position**: The player’s field position (e.g., midfielder, striker).
- **Goals**: Total goals scored during the season.
- **Assists**: Number of assists provided.
- **Minutes Played**: Total minutes the player has been on the fiel#d.

#### 2. EA Sports Dataset
This dataset contains the FIFA 2024 ratings and potential scores for football players globally. It includes attributes like pace, dribbling, shooting, and physicality, as well as an overall potential rating that predicts a player’s growth over time. Key features include:
- **Overall Rating**: A score representing the player's overall skill level.
- **Potential Rating**: A projection of the player’s future potential.
- **Physical Attributes**: Metrics such as height, strength, and stamina.
- **Technical Skills**: Ratings for skills like passing, shooting, and dribbling.

#### Key Questions & Hypotheses

As we delve into the comparison between real-life player performance and their potential as rated by EA Sports, the following key questions and hypotheses will guide our analysis:

1. **Are high-potential players performing better in real life?**
   - Hypothesis: Players with higher potential ratings in EA Sports are more likely to perform well in real-life matches (e.g., scoring more goals or providing more assists).
   - Investigative Question: Do players with an EA potential rating above 85 show statistically better real-life performance in terms of goals, assists, and key defensive actions?

2. **Which players are over-performing their potential?**
   - Hypothesis: Some players may outperform their EA Sports potential rating, indicating they are undervalued or underrated in the game.
   - Investigative Question: Are there players with an EA potential rating below 80 who have exceeded expectations by delivering top-tier real-life performances?

3. **Are younger players (under 23) living up to their potential?**
   - Hypothesis: Younger players with high potential ratings are expected to show significant real-life growth, especially in the top 5 leagues.
   - Investigative Question: How do real-life performances of young players under 23 years old compare to their EA potential ratings? Are they meeting or exceeding expectations?

4. **What is the relationship between a player's position and their real-life vs potential performance?**
   - Hypothesis: Certain positions (e.g., forwards or midfielders) may have a stronger correlation between EA potential ratings and real-life performance.
   - Investigative Question: Does a forward with a high potential rating (e.g., above 90) show a greater impact on goals and assists than a similarly rated defender’s impact on defensive metrics?

5. **Do players from certain leagues consistently outperform or underperform their potential?**
   - Hypothesis: Players from specific leagues (e.g., Premier League, La Liga) may perform closer to their EA potential compared to players in other leagues.
   - Investigative Question: Are players in the Premier League more likely to meet or exceed their potential ratings compared to those in Serie A or Bundesliga?

In your **Conclusions and Insights** section, you’ll aim to synthesize the findings from your analyses to address the project goals, hypotheses, and key investigative questions. Here’s a structured format that you can follow, tailored to your project.


### 1. **Project Recap and Objectives**
   - **Brief Recap**: Football Player Performance & Potential Analysis is a project to analyse the performance of football players from the top 5 leagues in
Europe in the 2023/2024 season. The goal of the project is to evaluate how football players in the these leagues performed in the 2023/2024 season, focusing on key metrics such as goals, assists, defensive actions, and other relevant performance indicators and to compare real-life player statistics with their potential ratings provided by EA Sports to identify:
     - **Overperformers**: Players whose real-life stats exceed their EA ratings.
     - **Underperformers**: Players with high EA potential but lower-than-expected real-life performance.
   - **Objectives Overview**:
     - Identify overperformers and underperformers.
     - Investigate if EA Sports potential ratings align with real-life performance metrics.
     - Address position-specific, age-based, and league-based trends in performance vs. potential.

### 2. **Key Findings**
   - **Summary of Analysis for Each Hypothesis**:
     - **Hypothesis 1**: *Are high-potential players performing better in real life?*
       - **Findings**: We see that players witha higher potential than 85 have a higher performance index and this index is based on positional metrics. The boxplot shows that players in the "High Potential" category generally have a higher performance compared to those in the "Lower Potential" category. The median for the "High Potential" group is significantly higher than the median for the "Lower Potential" group.
       - **Visual Evidence**: <img src="potential.png" alt="Image Description">
       - **Insights**: The graph suggests a positive correlation between EA Potential and Positional Performance. Players with higher potential ratings tend to have better overall performance, with a wider range of performance outcomes which means high-potential players perform better in real life but there are diverse indices because of the different positions

     - **Hypothesis 2**: *Which players are overperforming their potential?*
       - **Findings**: From this analysis we find that most of the players who over performed had a lower potential and this is expected because players with a higher rating most likely had the correct potential assigned to them.  
       - **Visual Evidence**: <img src="overperformers.png" alt="Image Description">
       - **Insights**: From the visuals we see that most of the overperformers were from age 25 and below and most of them played in Ligue 1 and Bundesliga and this can be because those leagues have lower publicity and then a lot of players that are just coming up play there and they have not yet proved whta they can do because of reduced playing times.
         
       - **Hypothesis 3**: *Are younger players (under 23) living up to their potential?*
       - **Findings**: There is a positive correlation between EA Potential Rating and Performance Index for players below 23 years, indicating that players with higher potential ratings tend to have better overall performance.We also see that the young players have performance inde of 0 or very close to 0. The boxplot of Age to Potential also shows that players with age between 23-27 have a higher potentail to players below 27.
       - **Visual Evidence**: <img src="age.png" alt="Image Description">
       - **Insights**: This shows that most of the young players are living up to their potential and the ones with low performance index could be caused by them having limited playing time.
      
       - **Hypothesis 4**: *What is the relationship between a player's position and their real-life vs potential performance?*
       - **Findings**: For the relationship between players position and their potential rating we find from the graphs that goals and assist have more impact on the potential of a Forward than the tacles and interceptions have on defenders, also midfielders' potential are impacted more by assists and key passes and Goalkeepers are more impacted by saves and clean sheets.
       - **Visual Evidence**: <img src="position.png" alt="Image Description">
       - **Insights**: The variability of defenders ratings could be because of the limited metrics used to get their performance and the versatility of their positions because LBs and RBs will be rated more on crosses and progressive passes than CBs the same can be said for CDMs.
      
       - **Hypothesis 5**: *Do players from certain leagues outperform or underperform their potential?*
       - **Findings**: From the analysis we see that most of the overperformers were from Ligue 1 and the High potential players also performed well to meet their potentials. There were also outliers in the potentials to league average plot which means there was variability in the potentials. In the mean potential ratio plot, Ligue 1 also was the highest with Bundesliga being the last.
       - **Visual Evidence**: <img src="league.png" alt="Image Description">
       - **Insights**: The high performance of Ligue 1 could be bacause of the callibre of players they had in Mbappe, Messi and Neymar. this would also account for the variability in Potentials because they were soe of the highest rated players and the others would have paled in comparison to them.


### 3. **Broader Insights and Patterns**
**Position-Based Performance**
The analysis on position-based performance revealed unique correlations between EA potential ratings and actual performance across different player roles. 
   - **Forwards:** Players in forward positions tended to show a high alignment between EA potential and real-life performance metrics, especially in goals and assists. This suggests that EA ratings for forwards are fairly accurate predictors of their real-life impact in offensive play.
   - **Midfielders:** Potential ratings for midfielders were significantly influenced by key metrics such as assists and progressive passes. Real-life performance showed a reasonable match with EA potentials, with players who excelled in these areas often achieving or surpassing expectations.
   - **Defenders:** The correlation between EA potential and performance for defenders was less direct, likely due to variability in performance metrics for defensive roles (e.g., tackles vs. interceptions vs. progressive passes). Additionally, full-backs (RBs and LBs) with offensive duties, like crossing and passing, had slightly higher potential scores than center-backs.
   - **Goalkeepers:** For goalkeepers, performance indicators such as clean sheets and saves aligned closely with potential ratings, especially for high-performing keepers in top leagues. Their ratings appeared more reliable as predictors of performance compared to other positions.

**Age-Related Performance Trends**
When analyzing age-related trends, younger players under 23 showed both promise and variability:
   - **High Potential and Performance Correlation:** Players under 23 with high potential ratings generally demonstrated strong real-life performances, especially in offensive and midfield roles. This indicates that EA ratings effectively capture potential for younger, high-performing talents.
   - **Challenges for Lower Potential Players:** However, some younger players with lower potential scores tended to have inconsistent or lower real-life performance. This group included several emerging players with limited playing time, suggesting that the discrepancies might be due to developmental stages and limited match experience rather than lack of potential.
   - **Peak Ages (23-27):** Interestingly, players aged 23 to 27 often displayed higher potential ratings, matching their peak years for performance consistency. Younger players seem to benefit from these insights as they progress in their careers, reflecting EA’s general accuracy for this age bracket.

**League Comparisons**
Our league-wise analysis yielded fascinating insights into how different leagues impact player performance versus their EA potential ratings:
   - **Ligue 1:** Ligue 1 emerged as a standout league, with players not only meeting but often exceeding their EA potential ratings. This performance could be influenced by star players like Mbappé and other high-performing talents, creating a slight skew toward overperformance within the league.
   - **Premier League and La Liga:** Players in these leagues tended to align closely with their EA ratings, indicating that high-potential ratings were generally predictive of real-life output. This may reflect the consistency of competitive levels and playing conditions in these leagues.
  - **Bundesliga:** Bundesliga had the widest variability, with several outliers in both over- and underperforming players. This variability might be due to the diverse styles and roles within the league, suggesting that EA potential ratings are less reliable as predictors here compared to more straightforward leagues like the Premier League.

### 4. **Limitations and Considerations**
In interpreting the findings of this analysis, it’s essential to recognize several key limitations and contextual factors that may influence results:

- **Data Constraints**: The analysis was based on a single season’s data (2022/2023), which may limit the generalizability of findings over time. Additionally, the sample size of players is constrained to the top five European leagues, potentially excluding emerging talents from less prominent leagues that might offer further insights into player potential and performance. EA Sports potential ratings, while useful as a benchmark, may contain inherent biases or subjective judgments that influence how a player’s potential is evaluated, particularly for lesser-known or younger players.

- **Performance Metrics Variability**: Real-life player performance is highly dynamic and can fluctuate due to various factors such as team strategy changes, coaching adjustments, or individual form. Additionally, injuries or off-field issues can cause inconsistencies that are not reflected in a single-season analysis. Therefore, EA potential ratings may not always align precisely with in-season performance, especially if a player experiences significant changes in playing time, role, or physical condition. Future studies incorporating multi-season data could provide a more stable performance baseline for comparing EA potential and real-life outcomes.

### 5. **Final Summary and Takeaways**
In conclusion, this analysis reveals valuable insights into the correlation between EA Sports potential ratings and real-life player performance, especially within the context of Europe’s top five leagues during the 2022/2023 season. Overall, the findings suggest that EA potential ratings can serve as a reasonably reliable predictor for certain metrics, particularly for players in specific positions like forwards and midfielders, where performance aligns well with high potential ratings. High-potential players generally performed better in terms of goals and assists, validating EA’s rating system to some extent.

However, the analysis also highlights intriguing nuances, such as overperforming players with lower EA potential ratings, especially in leagues like Ligue 1, and the variability in performance among younger players. This suggests that while EA ratings offer valuable guidance, real-life performance can defy expectations due to factors like league dynamics, team strategies, or player growth curves. These takeaways underline the importance of combining potential ratings with actual performance data for a more comprehensive assessment in scouting and player evaluation.