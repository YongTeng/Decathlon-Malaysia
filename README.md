# Business Problem
The primary objectives of this influencer campaign, run by Decathlon's Domyos brand, were:
•	To rejuvenate its customer base by attracting Generation Z customers. <br />
•	To assess the profitability of the campaign. <br />

<p align="justify"> The aim was to use influencer marketing, specifically a live Instagram session by fitness influencer Sissy Mua, to appeal to younger audiences and increase Generation Z engagement with Decathlon's Cardio Fitness products.
Key questions to address: <br />
•	Was the target of recruiting more Generation Z customers achieved? <br />
•	Was the campaign profitable for Decathlon? <br />

# Business Intelligence Solution

![image](https://github.com/user-attachments/assets/b3be26ef-2023-40d4-9a92-605b4154c296)

<p align="justify"> To conduct a focused analysis, we utilized five key datasets: d_customers, flow_audience, d_business_unit, d_sku, and f_transaction_detail. These datasets provided customer demographics, product interactions, store information, SKU-level product details, and transaction data. We narrowed down our scope by filtering for specific model codes (7635140, 5015822, 7166996, 2486222) representing the main products in the campaign—leggings, bra, t-shirt, and shoes. Each model code is associated with specific SKUs, creating a hierarchical structure that links SKUs as subcategories within their primary models. By merging filtered SKU and transaction data with customer information, we formed a comprehensive dataset that enables targeted analysis of customer engagement and purchasing patterns within the female sportswear market, providing insights into the campaign’s impact on this audience segment.

# Data Processing

<p align="justify"> To conduct a focused analysis, we utilized five key datasets: d_customers, flow_audience, d_business_unit, d_sku, and f_transaction_detail. These datasets provided customer demographics, product interactions, store information, SKU-level product details, and transaction data. We narrowed down our scope by filtering for specific model codes (7635140, 5015822, 7166996, 2486222) representing the main products in the campaign—leggings, bra, t-shirt, and shoes. Each model code is associated with specific SKUs, creating a hierarchical structure that links SKUs as subcategories within their primary models. By merging filtered SKU and transaction data with customer information, we formed a comprehensive dataset that enables targeted analysis of customer engagement and purchasing patterns within the female sportswear market, providing insights into the campaign’s impact on this audience segment.


# Exploratory Data Analysis (EDA)

<p align="justify"> In the Exploratory Data Analysis (EDA) phase, we examined the filtered dataset to uncover patterns and trends related to customer demographics, purchasing behavior, and product popularity within the female sportswear market. By segmenting customer data by age and gender, we identified the dominant customer profiles and evaluated the effectiveness of the campaign in reaching its intended Generation Z audience. Sales data analysis by product type (leggings, bra, t-shirt, and shoes) and transaction status helped us understand product performance and customer satisfaction. We also analyzed transaction channels (online vs. offline) and device usage to assess digital engagement, with mobile devices showing a strong presence, reflecting current shopping trends. These insights provide a foundational understanding of customer interactions and purchasing behavior, enabling data-driven recommendations for future campaigns.


# Analysis 1: Group customers by age, and gender for customer segment analysis

<img width="452" alt="image" src="https://github.com/user-attachments/assets/df2a757c-fc1b-422a-9ca2-29c8b76a2d86">

<p align="justify"> The age distribution graph shows that the 41-50 age group forms the majority of female customers, while younger age segments, including Generation Z, are underrepresented. In the female sportswear market, especially for items like leggings and sports bras, younger audiences tend to be trendsetters. This age disparity suggests an opportunity to further engage younger female customers, who are often more influenced by social media trends and activewear fashion. Tailoring marketing efforts towards Generation Z and younger millennials through trend-focused campaigns and influencer partnerships could help brands attract a younger demographic that is more likely to embrace athleisure as both activewear and casual wear.

# Analysis 2: Transaction Status Visualization 

<img width="452" alt="image" src="https://github.com/user-attachments/assets/02016cc9-53f4-48a4-a9a1-dd4f9773db65">

<p align="justify"> The graph shows the transaction status count (canceled, finished, and shipped) for each model code: 2486222 (shoes), 5015822 (bra), 7166996 (leggings), and 7635140 (t-shirt). Across all products, the "finished" status has the highest transaction count, indicating successful completion of most transactions. The shoes and bras have particularly high finished transaction counts at 251 and 395, respectively. However, there are also notable cancellation counts for each product, especially the bra, with 105 canceled transactions. The "shipped" status, which represents transactions in transit or awaiting final delivery, has the lowest count across all products.

<p align="justify"> For the case study, these findings highlight a generally positive response to the campaign, as most transactions were completed successfully, suggesting customer satisfaction with the promoted items. However, the higher cancellation rates for specific products like the bra indicate potential issues with customer expectations or sizing that Decathlon could investigate further. To improve customer experience, Decathlon may consider enhancing product descriptions, providing detailed size guides, or gathering feedback on canceled orders to address possible concerns. Ensuring high completion rates and minimizing cancellations will reinforce customer trust and optimize the effectiveness of future campaigns.

#
<img width="452" alt="image" src="https://github.com/user-attachments/assets/bcc42a39-807f-4e8e-8889-e6f60acff1e6">


<p align="justify"> The purchasing pattern graph indicates that spending was highest among the 41-50 age group, with minimal expenditure from Generation Z. In the current market, younger women are often the most responsive to influencer marketing, particularly for athleisure items like leggings and sports bras. This suggests a missed opportunity, as Generation Z generally follows activewear trends closely. Tailoring campaigns to target younger female customers could potentially boost sales by leveraging social media platforms and influencers popular among this demographic to increase engagement with trend-driven products.!

# Analysis 3: Product Instock by Product ID Model (Available, Unavailable, Partially)

<img width="452" alt="image" src="https://github.com/user-attachments/assets/82278f04-bb13-41bd-9c4f-b1d335f660ff">

<p align="justify"> The chart shows that each product (leggings, bra, t-shirt, and shoes) was mostly available, with minimal instances of partial or unavailable status. High availability aligns with the rising demand for women’s sportswear, driven by growing interest in fitness and athleisure. Sports brands must ensure inventory readiness, as limited stock could lead to missed sales opportunities. For female consumers, the ability to purchase immediately after seeing an influencer recommendation is essential, especially for popular items like leggings and sports bras, which can sell out quickly. In this market, maintaining inventory during a campaign is crucial for capturing impulse purchases and satisfying demand.

# Analysis 4: Engagement Metrics by Device Type

<img width="452" alt="image" src="https://github.com/user-attachments/assets/4f3e941a-a771-4deb-b405-02019b064118">

<p align="justify"> The graph demonstrates that the majority of visitors accessed the platform via mobile (530,775), followed by desktop (170,146), and tablet (34,414). This device breakdown is particularly relevant in the female sportswear market, where mobile shopping is common, especially among younger audiences. Mobile devices allow for quick access to social media and online stores, creating a seamless shopping experience from influencer posts to purchase. For women buying sportswear, especially leggings and sports bras, this accessibility allows them to easily compare items and see reviews, while potentially being influenced by trends on platforms like Instagram. The high mobile usage suggests that optimizing the mobile shopping experience is critical to capturing this audience effectively.

# Analysis 5: Sales Performance and Revenue by Store Type

<img width="452" alt="image" src="https://github.com/user-attachments/assets/0539dc62-7778-4474-8aac-9c952ac0eb44">

<p align="justify"> The graph highlights the substantial difference in sales performance between digital and physical stores. With a total sales value of €198,165 from digital stores compared to -€1,405 from physical stores, it’s clear that online channels were far more effective. The preference for digital shopping in the female sportswear market reflects the convenience and tailored experience that e-commerce offers. Women purchasing items like leggings and sports bras often value detailed product descriptions, size guides, and customer reviews that digital platforms provide, especially when choosing functional sportswear. Additionally, online platforms allow customers to browse through an extensive range of brands, making it easier to find high-quality, trendy sports apparel.

# Business Recommendations

<img width="452" alt="image" src="https://github.com/user-attachments/assets/664e0e57-74d5-497a-bc9c-ea5c75679d6a"> (Source: statista)


<p align="justify"> The graph shows that Facebook (44%) and Instagram (25%) are considered the most important platforms by marketers worldwide, followed by LinkedIn (21%). Instagram, specifically, aligns well with younger demographics, including Generation Z, making it a strategic platform for reaching this audience with influencer-driven campaigns. For Decathlon’s campaign, continuing to leverage Instagram, where younger consumers are active, is essential for targeting Generation Z effectively, particularly in promoting trendy sportswear items like leggings and bras. 

#
<img width="452" alt="image" src="https://github.com/user-attachments/assets/8e768955-80ff-4cb1-81b9-c462b12e0ceb"> (Source: statista)



<p align="justify"> The graph shows that the largest share of Instagram users falls within the 18-24 (31.7%) and 25-34 (30.6%) age groups, aligning with Generation Z and young millennials. Since these demographics are highly engaged on Instagram, Decathlon’s campaign can focus on creating visually engaging content tailored to their interests, emphasizing athleisure and functionality. Using influencers who resonate with this age group, Decathlon can better appeal to these potential customers, enhancing the campaign's effectiveness and driving sales of sportswear items tailored to younger, trend-conscious consumers.


