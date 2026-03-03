# ABtest-Design
Web Analytics &amp; A/B Test Design (Conversion Rate Optimization)
## Project Goal
To diagnose a severe engagement issue where 75% of landing page visitors drop off without scrolling. 
The objective was to analyze user behavior metrics and design an A/B test to improve the scroll and conversion rates.

## Tools & Technologies
* **Exploratory Data Analysis (EDA):** Correlation analysis between session length, clicks, and scroll depth.
* **Business Frameworks:** ICE (Impact, Confidence, Ease) scoring for hypothesis prioritization.
* **Statistical Pre-analysis:** Sample size calculation, Minimum Detectable Effect (MDE), p-value, and statistical power simulations.

## The Process & Logic
1. **Problem Identification:** Discovered that the median session length was only 18 seconds, meaning users were landing, reading the hero section, clicking, and immediately leaving.
2. **Hypothesis Generation:** Used the ICE framework to score potential solutions. 
A 4-option desktop navigation menu ranked highest (Score: 27) as it removes the uncertainty of the current "Download Syllabus" button.
3. **Statistical Setup:**
   * **Baseline:** 25% scroll rate
   * **Target:** 35% scroll rate (a 40% relative uplift).
   * **Requirements:** Simulated a full 1-month test using the total traffic of 1,000 visitors/month (500 visitors per variation) to ensure robust data collection.
   * **Simulated Evaluation:** A successful test run at these metrics yielded a 99% Confidence Level and 99.5% Observed Power.

## Key Business Insights
* **The 18-Second Window:** The median visit lasts 18 seconds, which is just enough time to read the top hero section. We have exactly this 18-second window to capture attention and drive engagement before the user leaves.
* **Desktop vs. Mobile Engagement:** Mobile users scroll significantly more than desktop users. For users who clicked a button, the mobile scroll rate is 58.3% compared to 36.5% on desktop. For users who did not click, mobile scrolling is 28.5% versus 14% on desktop. This difference is likely due to mobile UX/UI naturally encouraging scrolling, indicating that the desktop layout requires optimization to offer similar exploration.
* **The "False Success" Click:** Users who stay less than 50 seconds have a 0% scroll rate but still click buttons 6.5% of the time. They are clicking blindly and leaving without reading the page.
* **Paid Marketing Inefficiency:** Paid ads consistently account for roughly 40% of traffic across both short and long sessions . Paid traffic performs no better than free traffic (25.8% scroll rate vs 25.0%) . This indicates ad messaging targets the wrong audience or does not match landing page content.
