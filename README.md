# Smart Fan Share of Voice (SoV) Analysis – Atomberg Internship

 
It builds an AI agent that analyzes the **Share of Voice (SoV)** for Atomberg and its competitors in the *smart fan* category.  

The workflow:
1. Scrape search results from **Bing** for the keyword `"smart fan"`.
2. Extract webpage content, titles, and snippets.
3. Detect brand mentions (Atomberg, Havells, Crompton, Orient, Usha) using **fuzzy matching**.
4. Perform **sentiment analysis** using TextBlob.
5. Compute metrics:
   - Mentions Count
   - Share of Voice (%)
   - Average Sentiment
6. Visualize results with **Plotly** (pie chart, bar chart, sentiment comparison).

---

## 🛠 Tech Stack
- **Python 3.9+**
- Libraries:
  - `requests` – Fetch search results and webpages
  - `beautifulsoup4` – Parse HTML
  - `textblob` – Sentiment analysis
  - `pandas` – Data handling
  - `plotly` – Data visualization
  - `rapidfuzz` – Fuzzy matching for brand mentions

---


