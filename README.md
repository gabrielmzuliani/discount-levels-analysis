# Project Background
The discount levels data analytics project was conducted using real-world data, the structure, methodology, and approach were designed to reflect business scenarios and ensures that the insights generated and the analytical framework applied can be replicated in organizational contexts.

This project foxuses on investigating the impact of discount strategies on business performance. Throught data analysis, it evaluates how the differents discounts levels influence key metrics, such as revenue, profit, and sales volume. The analysis aims to identify whether discounts effectively drive demand or negatively affect profitability. Additionally, it explores patterns across product categories and regions to uncover strategic opportunities. The main goal is to support more data-driven pricing decisions and improve financial outcomes.

Insights and recommendations are provided on the following key areas:
* **Main metrics relationship:** Analysis applied to identify and assess the dependency level between key business metrics as well as their pattern behavior.
* **Discount safe range:** Through analysis across different data segments generate a discount safe range that supports sustainable profitability.
* **Safe range simulation:** Application of the defined discount ranges to simulate their impact on business performance, enabling the assessment of more balanced and effective pricing strategies.

The python code executed can be found [here.](https://github.com/gabrielmzuliani/discount-levels-analysis/blob/main/sales-analysis.ipynb) <br>
The dataset used can be found [here.](https://github.com/gabrielmzuliani/discount-levels-analysis/blob/main/stores_sales_forecasting.csv)

# Executive Summary
### Overview of Findings:
The correlation analysis shows that discounts have a strong negative relationship with profit margin and a moderate negative impact on total profit, while having negligible influence on revenue and quantity sold. This indicates that the current discount strategy is not generating the expected increase in demand and is instead eroding profitability. 

<img width="1020" height="808" alt="image" src="https://github.com/user-attachments/assets/40c05c17-4890-4880-9992-515b9d2078f5" />

### Revenue and Profit Behavior by Discounts Applied:
* Large discounts don’t increase revenues
*	0% - 10% (Safe Zone): In this range the profit is still positive, the margin is healthy and the revenues increase by 10%.
*	10% - 20% (Medium Discount): In this range margin is still applicable, however, the margin collapses quickly.
*	High Discounts (> 30%): In this range, profit and margin become negative and revenues don’t compensate.

The analysis reveals a non-linear relationship between discounts and business performance. While lower discounts (up to 10%) can increase revenues without significantly harming profitability, higher discounts levels lead to a sharp decline in profit margin and consequently generate losses. This indicates that the company is over-discounting beyond the optimal threshold, resulting in value destruction.

<img width="1062" height="699" alt="image" src="https://github.com/user-attachments/assets/726432ef-d9c0-47d1-9ac6-4126cee68276" />

### Discount Levels by Sub-Categories:
*	Discounts above 30% consistently lead to negative profitability across all sub-categories and should be avoided.
*	A 10% discount is generally safe and maintains positive profitability across observed sub-categories.
*	A 15% discount significantly reduces margin and may represent a risk, particularly for Bookcases.
*	At 20%, only Furnishings maintain a relatively healthy margin, while other sub-categories may represent severe margin compression or losses.

The analysis shows discount sensitive behavior across all sub-categories. While small discounts are generally safe, higher discounts levels erode profitability, particularly for Bookcases and Tables. Furnishings show great tolerance for higher discounts levels (Up to 20%). This indicates that a one-size-fits-all discount strategy is suboptimal, and a category-specific approach is required.

<img width="1459" height="429" alt="image" src="https://github.com/user-attachments/assets/cd98b7c4-f79d-4654-a20c-95d2c6a02d81" />

### Discount Levels by Regions:
*	Discounts above 30% consistently lead to negative profitability across all sub-categories and should be avoided.
*	Discounts around 20% introduce significant margin compression across all regions, with slightly higher risk observed in the West region.
*	Discounts up to 15% remain generally profitable across all regions, although they reduce profit margins and should be monitored.

The regional analysis shows that discount behavior is consistent across geographic areas, with all regions maintaining profitability at lower discounts levels and experiencing losses beyond 30%. While some variation exists, particularly in the West regions, overall analysis suggests that geography plays a secondary role. When combined with sub-categories analysis, it becomes clear that product characteristics are the primary driver of discount sensitivity. Therefore, discounts strategies should be primarily defined at the product level, with reginal adjustments as secondary consideration.

<img width="1461" height="429" alt="image" src="https://github.com/user-attachments/assets/e1b84de4-9de5-47a0-b46a-29670eb084fa" />

### What-If Simulation:
This simulation was conducted to evaluate how adjusting discount levels could improve the company’s profitability. Discount threshold defined by sub-category and region were combined to create a realistic and structured pricing scenario, allowing for a more accurate assessment of the current strategy’s impact.

The analysis demonstrates that existing discount practices are negatively affecting profitability, particularly due to excessive discounting in several transactions. By applying more disciplined and controlled discount levels, the simulation shows a significant improvement in financial performance.

Overall, the results indicate that a structured discount strategy would have substantially increased profitability by approximately 13 times on average per year, while maintaining a balanced approach that does not rely on aggressive pricing changes.

<img width="1020" height="700" alt="image" src="https://github.com/user-attachments/assets/1d3822cb-387c-4ebf-ba00-cd19d79e4373" />

# Results

The analysis results show a reactive discount approach which is unbased in a driven strategic data plan resulting in a lack of demand sensibility which does not adjust according to the levels applied and consequently erodes profitability.

To comprehend the current structure and implement a safe discount range a global data analysis was performed as well as by breakdown of sub-categories and regions fields in order to understand your effectiveness in different analysis levels. The result led us to a safe range up to 20%, however, case by case need to be evaluated considering the region and product.

To conclude a simulation was performed to visualize the effect of the suitable use of discount levels. The result not only showed the negative impact of an unsuitable discounts strategy as well as how to turn it suitable could maximize profitability generation that in this case was approximately 13 times on average per year.

# Recommendations
1.	**Understand the different discount levels:** The analysis shows that the current discount strategies stimulated the negative profit generation in many sales. Therefore, the company needs to offer different discount levels based on a data-driven approach that returns a suitable discount range to work with.
* Identify and reduce excessive discounts levels in addition to implementing a maximum discount threshold policy to prevent extreme discounts practices. 
*	Shift from a reactive discounting approach to a data-driven pricing strategy, using historical performance to guide discounts decisions and to monitor the impact on key metrics to ensure that promotional actions generate real value business.
*	Understand your categorical data to promote an adaptative model that leads to generating a smart strategy that turns out suitable for different situations.

👉 Expected impact: Improved profitability through more controlled and strategically applied discount levels.

2.	**Study the demand behavior:** The analysis shows that in many cases the higher applied discount levels were not a determinant factor to increase the sales volume, therefore, a study of demand to understand your consumer pattern could be suitable to generate effective strategies.
*	Identify the main factors influencing purchase decisions beyond price.
*	Identify products with low sensitivity to discounts.
*	Investigate non-price drivers of demand, such as product quality, brand perception, customer experience, and availability.
*	Evaluate the impact of timing and frequency of promotions, ensuring discounts are applied strategically rather than uniformly

👉 Expect impact: Maximization of business value by aligning pricing strategies with customer behavior, while promoting stronger customer engagement and loyalty.

**Additional Considerations:**

While the analysis highlights the importance of optimizing discount strategies, it is important to recognize that profitability is influenced by multiple factors beyond pricing. Elements such as cost structure, product mix, customer segmentation, operational efficiency, and competitive positioning may also have a significant impact on financial performance.

Therefore, it is recommended that future analyses incorporate these dimensions to provide a more comprehensive understanding of profitability drivers. By combining pricing optimization with broader business insights, the company can develop more sustainable and effective strategies for long-term growth.
