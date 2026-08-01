# NBA-Injury-Risk-Analysis

This project analyzes nine seasons of NBA player data (2010–2019) to identify factors most correlated with injury risk and uses those findings to develop a composite Injury Risk Score (IRS) that classifies players into risk tiers.

The project is divided into two sections. Section 1 conducts exploratory data analysis in Excel to examine the relationship between injury frequency and factors including age, position, workload, and prior injury history, with findings presented via a dynamic dashboard. Section 2 uses those findings to empirically derive weights for the IRS formula, delivered through an Excel workbook with a VBA-powered player lookup tool that allows a user to retrieve any player's full injury history and current risk tier.

The methodology is intentionally modeled on actuarial risk classification principles. The goal is not to predict injuries with certainty but to quantify relative risk based on observable historical factors, the same way an actuary estimates mortality or morbidity risk from measurable inputs.

Status: In progress - finished separating injury data by season and assigning injury severity score to each injury report. Then, added for each player per season was the total number of injury reports and a total injury severity score (ISS) (not to be confused with the final IRS which will be developed later).

Next: a dynamic dashboard will be created to analyze trends based on aforementioned indicators.
