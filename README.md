<h1>Recommendation System</h1>

A content-based movie recommendation system built using Natural Language Processing (NLP) and Machine Learning, designed to recommend movies based on semantic similarity between movie metadata.
This project demonstrates a complete end-to-end ML pipeline — from raw data preprocessing to vectorization and similarity-based recommendations.

<h3> ⚔️ Plot overview</h3>

➢Genres<br>
➢Keywords<br>
➢Cast<br>
➢Crew<br>

By converting these attributes into numerical vectors and computing similarity scores, the system recommends movies that are contextually similar to a given input movie.

<h3>🚀 Key Features</h3>

➢Content-based recommendation <br>
➢NLP-driven text preprocessing<br>
➢Efficient similarity computation using cosine similarity<br>
➢Scalable vector representation with controlled vocabulary size<br>
➢Clean and modular preprocessing pipeline<br>

<h3>🧠 System Architecture</h3> 

➢Data Collection<br>
➢Movie metadata dataset containing overview, genres, keywords, cast, and crew<br>
➢Feature Engineering<br>
➢Merge multiple textual attributes into a single unified feature (tags)<br>
➢Text Preprocessing<br>
➢Token joining<br>
➢Lowercasing<br>
➢Stop-word removal<br>
➢Stemming using Porter Stemmer<br>
➢Vectorization<br>
➢Bag-of-Words model using CountVectorizer<br>
➢Similarity Computation<br>
➢Cosine similarity between movie vectors<br>
➢Recommendation Output<br>
➢Top-N similar movies returned for a given movie title<br>

<h3>🛠️ Technologies Used</h3>
➢Libraries<br>
➢Programming Language:	Python<br>
➢Data Manipulation: Pandas, NumPy<br>
➢NLP	NLTK (Porter Stemmer)<br>
➢Machine Learning: Scikit-learn<br>
➢Vectorization	CountVectorizer<br>
➢Similarity Metric	Cosine Similarity<br>

<h3>⚙️ Data Preprocessing & Feature Engineering</h3>

Applied:
➢Lowercasing for normalization<br>
➢Stop-word removal to reduce noise<br>
➢Porter Stemming to reduce word sparsity <br>

This ensured a compact and semantically meaningful vocabulary.

<h3>📈 Results & Observations</h3>

➢Successfully generates relevant recommendations based on content similarity<br>
➢Handles real-world textual noise and sparse data effectively<br>
➢Demonstrates strong alignment between semantic movie themes<br>

<h3>📚 Learning Outcomes</h3>

➢Practical application of NLP in recommendation systems<br>
➢Strong understanding of text preprocessing and vectorization<br>
➢Hands-on experience with cosine similarity and feature engineering<br>
➢Exposure to real-world data handling challenges in pandas<br>

<h3>📂 Project Structure</h3><br>
├── data/<br>
│   └── movies.csv<br>
├── notebook/<br>
│   └── movie_recommendation.ipynb<br>
├── README.md<br>
└── requirements.txt
