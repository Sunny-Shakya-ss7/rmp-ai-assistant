# Rate My Professor AI Assistant

An AI-powered platform designed to help students make informed decisions when selecting courses and professors. Leveraging advanced natural language processing and sentiment analysis, this assistant provides detailed insights into professor ratings, reviews, and teaching styles.

# Technologies Used

- NextJS
- Pinecone
- OpenAI
- Meta/llama-3.1 LLM
- HuggingFace embeddings

# Future 

- [ ] Implement a feature that allows users to submit links to various professors' pages on Rate My Professor. The data from these web pages should then be automatically scraped and inserted into Pinecone.
- [ ] Implement an advanced search and recommendation system that allows users to query and receive personalized professor recommendations based on input criteria
- [ ] Integrate sentiment analysis and trend tracking to provide insights into changes in professor ratings and review sentiments over time.
- [ ] Smart-Review Summarization: Automatically generates concise summaries of student reviews, highlighting common themes, strengths, and areas for improvement.
- [ ] Personalized Recommendations: Suggests professors and courses based on a student's learning preferences, major, and past course performance.
- [ ] Sentiment Analysis: Analyzes the tone and sentiment of reviews to provide an overall positivity/negativity score for each professor.
- [ ] Interactive Q&A: Allows students to ask specific questions about professors, and the AI provides answers based on aggregated review data.
- [ ] Trend Analysis: Tracks changes in a professor's ratings over time, helping students understand trends in teaching effectiveness or student satisfaction.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Also install python libraries:

```
pip install -r requirements.txt 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
