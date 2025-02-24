
---

## 🚀 QuickNews - Autonomous AI News Agent 🤖📰

**QuickNews** is an intelligent AI agent that autonomously searches, summarizes, and publishes news articles. Built as an industry-ready application, it streamlines the process of gathering and publishing news content with zero human intervention.

### 🎯 Project Overview
- Web crawling and data extraction from reliable news sources
- Intelligent content summarization and structuring
- SEO optimization for better discoverability
- Automated publishing to Hashnode
- Support for multiple languages
- AI-generated imagery for enhanced visual appeal

### 🛠️ Technical Approach
**Data Collection & Processing**
- Uses DuckDuckGo API for fetching recent news
- Implements `newspaper3k` for article parsing
- Utilizes NLTK for NLP and summarization

**Content Generation**
- Employs extractive summarization techniques
- Generates SEO-optimized titles and descriptions
- Creates AI-generated illustrations with Pollinations.ai

**Publishing Pipeline**
- Formats content in Markdown
- Optimizes images
- Publishes to Hashnode via GraphQL API
- Supports 10+ languages using Google Translate

### ✨ Features
- 🌐 **Multi-source News Aggregation**
- 📝 **Smart Summarization**
- 🎨 **AI Image Generation**
- 🌍 **Multilingual Support**
- 📊 **Clean UI** with Streamlit
- 🚀 **One-Click Publishing** to Hashnode

### 🔧 Setup & Installation
```bash
git clone https://github.com/yourusername/quicknews.git
cd quicknews
pip install -r requirements.txt
```

Configure API tokens in `Final_name.py`:
```python
self.api_token = "Your_hashnode_api"
self.publication_id = "Publication_id"
```

Run the application:
```bash
streamlit run main.py
```

### 🎮 Usage
1. Launch the app
2. Enter your search topic
3. (Optional) Add location for specific news
4. Select display language
5. Click **Search News**
6. Review summaries
7. Click **Publish to Hashnode**

### 🔑 Required API Keys
- Hashnode API Token
- Hashnode Publication ID

### 🤝 Contributing
Feel free to fork the repo and submit pull requests. Open issues for major changes.

### 🎓 Acknowledgments
- Built for **Flipr Hackathon 25**
- Uses **newspaper3k**
- Powered by **Streamlit**
- Thanks to **Hashnode** for their GraphQL API
