<h1 align="center">Market Performance Analysis</h1>

<table>
<tr>
<td>
 <h2 align="center">Company Overview</h2>

**Cupcakes & Coffee** is a Netherlands based café chain that operates across 7 city regions, offering artisanal cupcakes and specialty coffee.

Since launching, the brand has grown steadily and developed a loyal customer base, but management sees untapped potential in emerging markets. To achieve sustainable expansion, Cupcakes & Coffee seeks to identify new locations for strategic growth through a data-driven analysis of sales, customer reach, product demand, and regional performance.

Reporting to the **Head of Strategy and Business Development**, a market performance review was conducted to identify the top 3 cities with the strongest combination of demand, profitability, and long-term growth viability.

The analysis focused on the following **metrics:**

 •	**Sales Trends:** Measuring total revenue and order volumes across cities.

 •	**Customer Reach:** Evaluating potential market size and coffee-drinking population per city.

 •	**Product Performance:** Evaluating potential market size and coffee-drinking population per city.

 •	**Profitability Ratio:** Comparing average revenue per customer to average rent per region.
</td>
</tr>
</table>

<h1 align="center">Executive Summary</h1>
<h3 align="center">How sales performance evolved with shifting demand and growth</h3>
 
<p align="center">
 <img width="575" height="323" alt="{BEB72465-DF1E-4E0C-8985-78C82314C294}" src="https://github.com/user-attachments/assets/fffbb9a7-33af-4f6d-a708-597c8ae201c8" />
<tr>
<td style="width: 50%; border-right: 1px solid #ddd; padding-right: 20px;">

<table>
<tr>
<td>
 
1. **Revenue Growth and Peak Performance:**
   - October 2023 marked the strongest performance period, with a 195% month-over-month sales growth, indicating a sales surge possibly driven by seasonal or promotional events.
   - Following this peak, sales remained strong through November 2023 to February 2024, sustaining healthy revenue levels above $15K.
   - March 2024 saw a secondary recovery, growing 16% month-over-month, reinforcing consistent buyer activity in Q1 2024.

2. **Declining Trend in 2022**
   - Noticeable downturns occurred in April (–73%) and May (–32%), signaling potential seasonal demand dips or a slowdown in returning customers.
   - Despite these declines, sales stabilized from June through September, showing small but steady gains between +1% to +23%.
   - These fluctuations indicate a pattern of cyclical sales volatility, with rapid surges followed by short recovery periods.

</td>
<td style="width: 50%; padding-left: 20px;">

3. **Quarterly Insights & Seasonal Trends**
   - Q3 and Q4 2023 demonstrated the strongest revenue periods, with October’s performance far surpassing the annual average.
   - Early 2024 showed moderate performance overall, led by March and July growth spikes, suggesting that strategic marketing during recovery months can maintain consistent performance.
   - The data suggests post-peak stabilization rather than continued exponential growth — ideal for planning retention-focused campaigns.

4. **Key Takeaways & Recommendations**
   - Investigate drivers of October’s 195% surge (e.g., seasonal events, promotions, or product launches) to replicate success in similar months.
   - Mitigate sales slumps during April–May by scheduling marketing pushes, product campaigns, or loyalty initiatives in advance.
   - Capitalize on high-growth months (Oct, Mar, Jul) to refine promotion timing and strengthen overall year-round stability.
   - Refocus efforts on sustaining momentum after spikes by improving repeat customer engagement and monitoring conversion efficiency post-peak.
</td>
</tr>
</table>

<h2 align="center">Dataset Structure</h2>

The dataset consists of 4 key tables that form the analytical backbone of the project: **Sales, Products, Customers, City**
Relationships were established between Sales, Products, Customers and City tables in the **entity relationship diagram (ERD)** shown below to calculate sales per capita, profitability per region, and growth trends over time.

<h2 align="center">Key Findings</h2>

<h3 align="center">Sales Trends</h3>
<table align="center" width="1200" cellspacing="0" cellpadding="0" style="border-collapse:collapse;">
  <tr>
    <td width="33%" style="border:1px solid #ddd; border-right:none; padding:10px; vertical-align:top;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/6dc26a78-e0b2-42a1-81da-b00e45c7d621" alt="Sales Revenue" width="380" style="display:block; margin:0 auto;">
    </td>
    <td width="33%" style="border:1px solid #ddd; border-right:none; padding:10px; vertical-align:top;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/54195b08-ac37-4fc4-a674-34e1490c2f16" alt="Total Orders" width="380" style="display:block; margin:0 auto;">
    </td>
    <td width="34%" style="border:1px solid #ddd; padding:10px; vertical-align:top;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/b4a09f80-ef8f-4fe0-9dee-7dfd8ed6ab90" alt="Avg Revenue per Sale" width="380" style="display:block; margin:0 auto;">
    </td>
  </tr>
  <tr>
    <td colspan="3" style="border:1px solid #ddd; padding:20px; background-color:#f9f9f9;">
      1. South Holland and Groningen lead in total revenue, each surpassing $42K in sales.<br><br>
      2. Cupcake sales dominate, with Classic Vanilla, Chocolate Fudge, and Red Velvet as bestsellers.<br><br>
      3. Groningen shows strong sales consistency throughout the year, signaling steady customer loyalty.
    </td>
  </tr>
</table>

<h3 align="center">Customer Reach</h3>
<table align="center" width="1200" cellspacing="0" cellpadding="0" style="border-collapse:collapse;">
  <tr>
    <td width="50%" style="border:1px solid #ddd; border-right:none; padding:10px; vertical-align:top;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/3785fa44-3bb2-46b1-8772-86ebb722cd9f"
           alt="Largest Coffee Consumers by City" width="520" style="display:block; margin:0 auto;">
    </td>
    <td width="50%" style="border:1px solid #ddd; padding:10px; vertical-align:top;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/1dcb888f-1adb-4529-8e88-cbe52a7d98e4"
           alt="Highest Revenue Generating Cities" width="520" style="display:block; margin:0 auto;">
    </td>
  </tr>
  <tr>
    <td colspan="2" style="border:1px solid #ddd; padding:20px; background-color:#f9f9f9;">
      1. Randstad boasts the largest estimated 2.08M coffee consumers, followed by Amsterdam (980K) and Rotterdam Metro (680K).<br><br>
      2. These cities represent prime opportunities for expanding brand visibility and customer reach.
    </td>
  </tr>
</table>

<h3 align="center">Product Performance</h3>
<table align="center" width="1200" cellspacing="0" cellpadding="0" style="border-collapse:collapse;">

  <!-- 1) Top 5 Revenue Generating Products Over Time (boxed) -->
  <tr>
    <td style="padding:10px; vertical-align:top; border:1px solid #ddd;">
      <img src="https://github.com/user-attachments/assets/228e4b02-b38b-47c5-9ba5-8263e31df585"
           alt="Top 5 Revenue Generating Products Over Time"
           width="100%" style="display:block; max-width:1180px; margin:0 auto;">
    </td>
  </tr>

  <!-- Spacer -->
  <tr><td style="height:20px; background:#ffffff;"></td></tr>

<table>
<tr>
<td style="width: 50%; border-right: 1px solid #ddd; padding-right: 20px;">
 
1. **Revenue Growth and Peak Performance:**
   - October 2023 marked the strongest performance period, with a 195% month-over-month sales growth, indicating a sales surge possibly driven by seasonal or promotional events.
   - Following this peak, sales remained strong through November 2023 to February 2024, sustaining healthy revenue levels above $15K.
   - March 2024 saw a secondary recovery, growing 16% month-over-month, reinforcing consistent buyer activity in Q1 2024.

2. **Declining Trend in 2022**
   - Noticeable downturns occurred in April (–73%) and May (–32%), signaling potential seasonal demand dips or a slowdown in returning customers.
   - Despite these declines, sales stabilized from June through September, showing small but steady gains between +1% to +23%.
   - These fluctuations indicate a pattern of cyclical sales volatility, with rapid surges followed by short recovery periods.

</td>
<td style="width: 50%; padding-left: 20px;">

3. **Quarterly Insights & Seasonal Trends**
   - Q3 and Q4 2023 demonstrated the strongest revenue periods, with October’s performance far surpassing the annual average.
   - Early 2024 showed moderate performance overall, led by March and July growth spikes, suggesting that strategic marketing during recovery months can maintain consistent performance.
   - The data suggests post-peak stabilization rather than continued exponential growth — ideal for planning retention-focused campaigns.

4. **Key Takeaways & Recommendations**
   - Investigate drivers of October’s 195% surge (e.g., seasonal events, promotions, or product launches) to replicate success in similar months.
   - Mitigate sales slumps during April–May by scheduling marketing pushes, product campaigns, or loyalty initiatives in advance.
   - Capitalize on high-growth months (Oct, Mar, Jul) to refine promotion timing and strengthen overall year-round stability.
   - Refocus efforts on sustaining momentum after spikes by improving repeat customer engagement and monitoring conversion efficiency post-peak.
</td>
</tr>
</table>

<table align="center" width="1200" cellspacing="0" cellpadding="0" style="border-collapse:collapse;">
<!-- 3) Bottom chart (boxed and perfectly aligned) -->
<tr>
  <td style="border:1px solid #ddd; padding:5px; background-color:#ffffff; vertical-align:top;">
    <img src="https://github.com/user-attachments/assets/b7579e37-82be-4a40-8219-7ae7552f8be3"
         alt="Top 10 Product Sales by City"
         width="100%" style="display:block; width:1180px; margin:0 auto; border:1px solid #ddd;">
  </td>
</tr>
</table>

<h3 align="center">Profitability by City</h3>

<table align="center" width="1200" cellspacing="0" cellpadding="0" style="border-collapse:collapse;">
  <tr>
    <!-- Full-width centered profitability chart -->
    <td style="border:1px solid #ddd; padding:10px; text-align:center;">
      <div style="text-align:center; color:#5E17EB; font-weight:600; margin-bottom:6px;"></div>
      <img src="https://github.com/user-attachments/assets/80e40d02-ab48-4cf0-84c6-e739279715d3"
           alt="Profitability by City Chart" width="1150" style="display:block; margin:0 auto;">
    </td>
  </tr>

  <tr>
    <td style="border:1px solid #ddd; padding:20px; background-color:#f9f9f9;">
      1. South Holland and Groningen maintain the highest revenue-to-rent ratio, ensuring financial efficiency.<br><br>
      2. Randstad and Amsterdam generate high revenue but incur greater rent costs, reducing net margins.
    </td>
  </tr>
</table>

<h2 align="center">Recommendations</h2>

These are the recommendations based on the key findings:

<h3 align="left">1. Market Expansion Strategy</h3>

 - Prioritize South Holland, Utrecht Metro, and Amsterdam for new store openings.
   
 - Focus expansion budget on regions showing a balance of high revenue and low rent.

<h3 align="left">2. Product Portfolio Optimization</h3>

- Increase production and marketing for bestsellers (Classic Vanilla, Chocolate Fudge, Red Velvet).

- Reduce low-performing SKUs to streamline operations and maximize profitability.

<h3 align="left">3. Operational Efficiency</h3>

- Negotiate rent reductions in Randstad and Amsterdam where operating costs remain high.

- Leverage low-cost models from South Holland for scalability across new locations.

<h3 align="left">4. Growth Acceleration</h3>

- Replicate South Holland and Groningen’s customer engagement strategies in emerging regions.

- Launch targeted marketing campaigns during high-demand months (Q3–Q4).

<h3 align="left">5. Strategic Investment Priorities</h3>

- Allocate 60% of expansion funding to South Holland, Utrecht Metro, and Amsterdam.

- Expand presence strategically in high-demand urban centers while maintaining visibility in smaller markets.

 <h2 align="center">Assumptions</h2>

 For the purpose of this analysis, it was assumed that 25% of the Dutch population consumes coffee.

 <h2 align="center">General note</h2>

 The interactive dashboard of this project can be viewed here.
