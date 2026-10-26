
Human vs AI Text Detection & Analysis

An end-to-end Natural Language Processing (NLP) and Exploratory Data Analysis (EDA) pipeline designed to identify structural, grammatical, and complexity patterns distinguishing human writing from AI-generated text.

📊 Dataset Properties

The notebook processes a balanced dataset of 5,000 text samples (HumanVsAI-2026.csv):
• Human Samples: 2,462 | AI Samples: 2,538
• Features Analysed: text, label (Human/AI), source (medium), complexity_score, grammar_errors_count, and sentence_length.


🛠️ Pipeline Features

• Text Preprocessing: Lowercasing, removing URLs/HTML tags/numbers/punctuation, tokenization, stopword removal, and WordNet lemmatization.
• Feature Engineering: Extracts structural metrics including raw character lengths, average word lengths, and post-cleaned sentence lengths.

📈 Key Insights & Visualizations

• Distributions: Histograms reveal that AI text maintains strict, uniform lengths, while human text displays highly varied patterns.
• Grammar & Complexity: Boxplots prove AI text clusters tightly near zero grammatical errors, while human text exhibits native slang, typos, and varied complexity ranges.
• Correlations: Heatmaps uncover linear alignments between character lengths, sentence weights, and complexity scores.
• N-Grams: Frequency charts show AI relying on structural strings ("machine learning", "deep learning"), whereas human text relies heavily on informal and colloquial phrases.

