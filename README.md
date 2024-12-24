### Building_Cricket_Fantasy_Team
Cricket Analytics & Linear Programming project to build fantasy teams from existing matches data

### Problem Statement
Build your fantasy teams for IND v SL 3 match T20 series 2022 & find out your avg points per team.

### Dataset Information
This dataset contains 3 CSV files namely 1) ind_sl_t20i_1st_2022_02_24 2) ind_sl_t20i_2nd_2022_02_26 3) ind_sl_t20i_3rd_2022_02_27

All these files contain 36 rows and 13 columns namely 1)SeriesId 2)MatchId 3)Player 4)PlayerId 5)Team 6)TeamId 7)Role 8)Sel	9)Credits	10)Series Points	11)PlayingXI 12)Points13)DT

### Instructions on how to run this project code on your system
Step 1 : Download this project repository as a zip file. 
Step 2 : Unzip the folder to your desired location 
Step 3 : If you don't have Anaconda installed, go to the Anaconda website and download the installer for your operating system (Windows, macOS, or Linux) 
and launch it. 
Step 4 : Launch Jupyter Notebook Interface from Anaconda Navigator after which opens in your default browser. 
Step 5 : Navigate to this project folder. 
Step 6 : When inside navigate to Fantasy Cricket Project > IND_VS_SL_T20I_2022_Fantasy_Team_Project.ipynb 
Step 7 : Open and Run the IND_VS_SL_T20I_2022_Fantasy_Team_Project.ipynb 
Step 8 : Wait for the file to complete executing the program and then check the output.

#### You can also test the code for your specific custom problem statement if you have such data for example, IND VS AUS 4th Test 2024.

### Purpose of solving the problem

Building a fantasy cricket team using existing matches data and Linear Programming (LP) with PuLP serves several purposes:

#### 1. Optimal Team Selection
LP ensures that the selected team maximizes or minimizes a specific objective, such as:
Maximizing total predicted points or performance based on historical data.
Balancing the cost of players under a predefined budget.
Constraints can be defined to ensure the team adheres to the rules of the fantasy game, such as player limits, roles (batsmen, bowlers, all-rounders, and wicketkeepers), and team quotas.

#### 2. Strategic Decision-Making
LP enables strategic decisions based on historical performance metrics like average runs, strike rates, economy rates, or consistency across players.
It helps fantasy players make data-driven choices rather than relying on intuition or biases.

#### 3. What-If Scenarios
LP models can simulate various scenarios, such as:
Building teams for specific match conditions (e.g., a spin-heavy team for slow pitches).
Testing the impact of excluding or including specific players based on injuries or recent form.

#### 4. Efficiency and Automation
Automates the process of evaluating hundreds of players and combinations to find the best team quickly.
Reduces manual effort and allows for dynamic updates as new match data becomes available.

#### 5. Learning and Insight
Teaches how optimization techniques like LP can solve real-world problems.
Provides insights into the trade-offs between budget, player performance, and team balance.

#### 6. Competitive Advantage
Gives a competitive edge in fantasy leagues by leveraging optimization to create statistically superior teams.
Ensures compliance with all rules while achieving the best possible performance outcomes.
By using PuLP, you can model this problem programmatically and solve it efficiently, even for large datasets. The solution will provide an optimal selection of players that adheres to the constraints of the fantasy cricket platform, offering the best chance of winning or scoring highly in the league.

