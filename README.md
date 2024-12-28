# LLM-Sentiment-Analysis

### User Distribution
<img width="527" alt="Screenshot 2024-12-28 at 8 04 11 PM" src="https://github.com/user-attachments/assets/7fafdf39-443e-458f-8ea3-830c603216ad" />

The majority of Xiaohongshu users are concentrated in the southeastern coastal region of China, with Guangdong Province standing out as a significant hub. Guangdong, historically a well-developed commercial region since ancient dynasties, continues to thrive as an economic powerhouse due to its advanced infrastructure, international trade connections, and vibrant urban centers like Guangzhou and Shenzhen. This economic vitality makes it a prime location for Xiaohongshu users who are likely affluent, trend-conscious, and eager to explore lifestyle-oriented content, including beauty and fashion products. Outside this southeastern concentration, two notable exceptions emerge: Beijing and Sichuan Province. Beijing, as China's cultural and political hub, attracts a diverse, affluent population aligned with Xiaohongshu's aspirational content. Similarly, Sichuan's status as a top tourist destination, famed for its cuisine and cultural appeal, draws users interested in beauty, travel, and dining, with Chengdu blending tradition and modern trends to expand the platform's reach. 

### Correlation
<img width="636" alt="Screenshot 2024-12-28 at 8 09 12 PM" src="https://github.com/user-attachments/assets/a67f81e1-f2d1-4b93-8992-3093d4015024" />

The correlation matrix indicates (media) interaction, likes and favourites (‘interaction_cnt’, ‘like_cnt’, ‘fav_cnt’, ‘media_interaction_cnt’) are highly contributed to identifying the post as a popular post on Xiaohungshu with all the correlation higher than 0.4 or even 0.5. Vice versa, robotic posts, and sentiment have a negative correlation with popular posts.

### Sentiment Classification
<img width="775" alt="Screenshot 2024-12-28 at 8 07 08 PM" src="https://github.com/user-attachments/assets/a7c53c74-1390-48e2-b16a-a246a0ab2bec" />
<img width="438" alt="Screenshot 2024-12-28 at 8 22 57 PM" src="https://github.com/user-attachments/assets/7f000e23-1c93-41e3-a64e-f8629fd8a830" />

The confusion matrix obtained by training the Ernie 3.0 reveals the classification distribution of each label, with the vast majority of labels correctly distinguished. Meanwhile, misclassification diminished with the less utmost sentiment, positive and negative being wrongly classified into neutral and others, reducing corresponding error arouse from false positive and false negative. While the neutral sentiment is still perceived as close to positive, Ernie 3.0 balanced its modelling performance with an increasing proportion of neutral sentiment mislabeled as negative

### WordCloud for postive sentiment
<img width="601" alt="Screenshot 2024-12-28 at 8 08 05 PM" src="https://github.com/user-attachments/assets/07e855fb-46ea-4758-8818-869813fc6af1" />

Positive sentiment content on Xiaohongshu often centers on users' satisfaction with beauty products, highlighting beneficial effects such as hydration, gentleness, and skin radiance. Concrete descriptions like "moisturizing," "mild," "refreshing," and "brightening" are commonly used, reinforcing the appeal of these products. This sentiment is further amplified by a persuasive tone, where users express strong personal feelings about their experiences. While these posts are framed as personal anecdotes, they subtly aim to influence others to purchase the same products. The prevalence of positive sentiment indicates that Xiaohongshu is widely perceived as a trustworthy platform for beauty product recommendations, fostering consumer trust in peer reviews and driving engagement.
