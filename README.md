# A new era in query languages: Large Language Models & The semantic paradigm

Google Cloud AI Query Engine (AIQE) was recently announced in Next25. Yoiu can read more in this link: https://cloud.google.com/blog/products/data-analytics/data-analytics-innovations-at-next25?e=48754805

AIQE is built on top of foundational work (AI.GENERATE() command) that was previously done in BigQuery. This repo' will provide code samples for using AI.GENERATE() and will compliment a Medium article that was written, by Lior (Leo) Ginzberg, on this subject

Below please find additional context about AIQE:

# Unlocking New Dimensions of Insight

AI Query Engine is available as a family of easy-to-use SQL functions, such as:
**AI Filter**. Filter data based on nuanced linguistic understanding. For example, identify highly satisfied customers from a corpus of support chat transcripts, not just by looking for the "satisfied" word but by the LLM understanding of the expressed sentiment.
AI Summarization: Summarize and analyze entire datasets with ease. For example, given a number of product reviews, summarize them into one paragraph.
**AI Join**: Intelligently join disparate datasets based on natural relationships. For example, link images of products with corresponding product descriptions, even without explicit identifiers, by having the LLM understand the products featured in each image.
**AI TopK**: Rank data based on real-world knowledge. For example, identify the companies most impacted by a regulatory action. 
…and many more.
SELECT AI.SUMMARIZE(f”Summarize these product reviews in one paragraph, paying extra attention to cost, quality, and reliability: {product_reviews.review_text}”) as summary
FROM product_reviews


# Bringing the Knowledge of the World into Your Analytics

AI Query Engine extends the capabilities of BigQuery beyond traditional data analysis by enabling users to incorporate the vast knowledge of LLMs. This opens the door to previously unimaginable insights, allowing users to understand not only "what" their data contains, but also "why" and "how" it relates to the broader world.
Empowering Users of All Levels
Designed with ease of use in mind, AI Query Engine's intuitive SQL functions are readily accessible to analysts with minimal technical expertise, while still providing the power and flexibility required by data scientists and data engineers. This democratization of AI-powered analytics enables organizations to leverage the full potential of their data, regardless of their teams’ technical aptitude.
“We wanted to analyze our images, documents, and videos. We just couldn’t”, according to Sean Pool, Head of Data at Erewhon,  a boutique online retailer. “We simply lacked the in-house expertise. AI Query Engine removes most of the complexity of working with unstructured data. With AI Query Engine, our business is supercharged on analytics, vastly improving our ability to segment and target users for ad campaigns, and staying two steps ahead of emerging customer needs.”

# Building the Future of AI Applications

AI Query Engine serves as a powerful foundation for building sophisticated AI applications. It dramatically simplifies the development of Retrieval-Augmented Generation (RAG) systems by enabling simpler, richer, and more relevant semantic-style information retrieval, even across multiple data modalities. This same semantic power amplifies the potential of AI agents, empowering them to reason over enterprise data in deeply meaningful ways. Finally, AI Query Engine trivializes complex transformations on multimodal data, allowing data engineers to seamlessly work with and derive insights from text, images, and more, all within a unified SQL interface.
To get started, simply try using one of the AI.__  functions in BigQuery Studio or Data Canvas, and be sure to head over to our documentation for interesting sample queries. 

