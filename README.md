# [Supernova-Exploratory-Analysis](https://docs.google.com/presentation/d/1TdMiqTbmwzESlSqQPlcXZTigy6VILZGas1UomqdvAic/edit?usp=sharing)

## Overview

The primary task of this externship project was to complete an initial, exploratory analysis of public health data in different regions of Canada. Public health inspection violations, or failures, indicate areas where businesses fail to comply with health and safety regulations, which could lead to higher operational risks. Inspection fail rates were calculated to find out how risky a business would be to insure, and the data was explored to find other potential areas of interest for deeper analysis. The original datasets included information on business health inspections, like date, time, business name and address, results, and any actions that were taken or need to be taken. Any findings were then presented to the CEO of Supernova through Google Slides and Zoom.

## The Process

The first step was to review and clean the raw data that was scraped from different regions' Public Health websites. The data had most of the required information, but there wasn't a clear pass or fail column. A pass/fail column was created to assign each row a 1 for fail and 0 for pass. To accomplish this, functions were used to search the results column or actions taken column for keywords or phrases that indicate a pass or fail. Using the pass/fail column, the top three biggest and smallest region's average fail rates were calculated and compared. This was done to look for any correlations between the size of the region a business is in and their likelihood of failing an inspection. It was then taken a step further to find out how likely a business was to fail a second inspection should they fail one. 

## Results

The top three biggest and smallest regions had very similar fail rates, so no major correlation was found. 

<img width="643" alt="image" src="https://github.com/user-attachments/assets/f24b841a-81ad-43cd-8db9-6e923dc25403" />
<img width="633" alt="image" src="https://github.com/user-attachments/assets/59cd6f11-0de6-452b-b12c-f4b06952855d" />

However, small region restaurants were about 8% more likely to pass an initial inspection and 8% less likely to receive additional violation after receiving the first.

<img width="541" alt="image" src="https://github.com/user-attachments/assets/a7f3e5d2-7172-42b5-8e09-d43045537574" />
