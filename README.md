# 🧠 News on TikTok – Modeling Video Performance

This project analyzes predictors of TikTok video performance using data from German-speaking news outlets in 2023.

## 📊 Project Overview
The goal of this project was to explore which video- and content-related characteristics influence the reach and engagement of TikTok news content.  
Analyses focused on both quantitative metadata (views, likes, shares) and textual features (video topics).

- Dataset: N ≈ 4,000 TikTok videos  
- Source: German-speaking news outlets (Germany, Austria, Switzerland)  
- Methods: Multiple regression & deep learning (LSTM)  
- Tools: Python (pandas, scikit-learn, tensorflow, matplotlib)  
- Performance: Regression R² ≈ .65 | Deep learning R² ≈ 0  

## 🧠 Research Focus
- Identify visual and auditory cues that predict higher view counts.  
- Explore whether free-text topics (“V11_general_topic”) alone can predict engagement.  
- Compare traditional statistical modeling to neural network performance.  

## 🧩 Key Findings
- Videos featuring a **journalist’s or moderator’s voice** performed slightly better.  
- **Background ambience** and **regional context** were positively associated with reach.  
- Deep learning models based solely on text failed to capture engagement patterns — confirming that **audiovisual cues** play a stronger role.  

## 💾 Data Source

**Dataset:**  
Wedel, L., Mayer, A.-T., & Batzner, J. (2025). *News on TikTok: An Annotated Dataset of TikTok Videos from German-Speaking News Outlets in 2023* (Version 2.0.0) [Data set]. GESIS, Cologne.  
https://doi.org/10.7802/2863  

**License:** CC BY-NC-SA 4.0 (Attribution – NonCommercial – ShareAlike)

## 👤 Author

Moritz Konstantin Kuhn  
Data Science & Communication Research  
📧 [moritzk.kuhn@gmx.com](mailto:moritzk.kuhn@gmx.com)  
🔗 [https://www.linkedin.com/in/moritz-konstantin-kuhn](https://www.linkedin.com/in/moritz-konstantin-kuhn)
