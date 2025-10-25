# shark_tank_analysis

Tools Used: Python(pandas),Tableau
Dataset: Shark Tank US dataset.csv(1441 pitches)

The project involved loading the raw data into Python (Pandas) for cleaning, where missing values were filled (0 for numbers, "Unknown" for text) and unused columns were dropped. cleaned dataset: cleaned_shark_tank.csv

The cleaned CSV was then analyzed to calculate key metrics (success rates, top investors)

The cleaned data was imported into Tableau to build two visual dashboards.
<img width="655" height="726" alt="image" src="https://github.com/user-attachments/assets/a5214bff-3bb3-49f1-9513-27c84976de02" />
<img width="649" height="717" alt="image" src="https://github.com/user-attachments/assets/29c96e7f-9fcb-46f3-8c21-4b6c88e32065" />

From the above dashboards we can infer that:
(1) High Success Rate: The analysis of 1,441 pitches shows a high overall success rate, with 61.21% of entrepreneurs (882/1441) successfully securing a deal.
(2) Top Investor: Mark Cuban is the most active investor on the panel, making a total of 263 deals.
(3) Dominant Industry: "Food and Beverage" is the most popular and successful industry, securing 188 deals—significantly more than any other category with Total Deal amount of $58,701,000
(4) Founder Success Pattern: There is a clear success pattern related to founder profiles. Mixed-gender teams had the highest success rate (66.3%), followed by female-only founders (63.6%). Both were more successful than male-only founders (58.1%).
(5) Valuation Negotiation: The data shows a major gap between requested and final valuations. On average, entrepreneurs requested valuations (avg. $3.66 million) are negotiated down by $1.46 million to an average final deal valuation of $2.20 million.

