🎬 CINÉMATHEQUE — Content-Based Movie Recommendation Engine

🍿 Discover Your Next Favorite Movie Through Intelligent Content-Based Recommendations

A beautifully designed vintage cinema-inspired movie recommendation engine powered by machine learning concepts and content similarity analysis.

📖 Overview

CINÉMATHEQUE is a browser-based movie recommendation system that suggests movies similar to films users already enjoy.

Unlike popularity-based recommendation systems, Cinematheque uses Content-Based Filtering, analyzing movie attributes such as:

* Genres
* Directors
* Cast Members
* Keywords
* Release Decade
* Themes

to generate highly relevant recommendations.

The application runs entirely in the browser with no backend or external APIs required.

🚀 Features

🎥 Intelligent Movie Recommendations

* Content-based filtering engine
* Similarity scoring system
* Top-K recommendation ranking
* Real-time recommendation generation

🔍 Smart Search

* Fuzzy title matching
* Typo correction support
* Partial title recognition
* Fast search experience

📊 Dataset Analytics

Interactive Exploratory Data Analysis (EDA) dashboard featuring:

* Genre Distribution
* Movies by Decade
* Rating Distribution
* Director Statistics
* Dataset Summary Metrics

🎨 Premium UI Design

* Vintage cinema aesthetic
* Marquee theatre-inspired layout
* Responsive design
* Interactive movie cards
* Elegant typography

📚 Sample Recommendation Scenarios

* Preloaded examples
* One-click testing
* Demonstrates recommendation quality

 Fully Offline

* No API keys required
* No server required
* Runs directly in browser
* Zero hosting cost

---

🧠 Machine Learning Concepts Used

Although implemented in JavaScript, this project demonstrates real-world recommender system concepts:

Content-Based Filtering

Movies are represented as feature vectors generated from:

```text
Genres
Director
Cast
Keywords
Release Decade
```

The recommendation engine compares movie feature vectors and finds the most similar films.

Feature Engineering

Each movie is transformed into a textual representation:

```text
Genres × 3 Weight
Director × 2 Weight
Cast Members
Keywords
Decade Tags
```

Example:

```text
Crime Crime Crime
Drama Drama Drama
Francis Ford Coppola
Francis Ford Coppola
Al Pacino
Marlon Brando
Mafia
Power
Family
1970s
```

Similarity Calculation

The recommendation system uses:

TF-IDF Vectorization

Converts movie features into numerical vectors.

Cosine Similarity

Measures similarity between movie vectors:

```math
Similarity(A,B)
=
(A · B)
/ (||A|| ||B||)
```

Higher similarity scores indicate more relevant recommendations.

Fuzzy Matching

Levenshtein Distance is used to:

```text
godfather → The Godfather

bladerunner → Blade Runner

intersteller → Interstellar
```

allowing users to search even with spelling mistakes.

📊 Dataset

The project includes a curated dataset containing:

| Metric         | Value       |
| -------------- | ----------- |
| Movies         | 200+        |
| Genres         | 14          |
| Time Span      | 1927 - 2023 |
| Average Rating | 7.4         |
| Median Runtime | ~120 mins   |

Dataset categories include:

* Crime
* Drama
* Thriller
* Sci-Fi
* Horror
* Romance
* Comedy
* Fantasy
* Mystery
* Adventure
* Animation
* Biography
* War
* Western

🏗️ Project Architecture

```text
User Search
      │
      ▼
Fuzzy Title Matching
      │
      ▼
Feature Extraction
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Cosine Similarity
      │
      ▼
Top-K Ranking
      │
      ▼
Movie Recommendations
```

🎯 Example Recommendations

Input

```text
The Godfather
```

Possible Recommendations

```text
The Godfather Part II
Goodfellas
Scarface
Heat
Once Upon a Time in America
```

---

Input

```text
Interstellar
```

Possible Recommendations

```text
Arrival
The Martian
Contact
2001: A Space Odyssey
Dune
```

📈 Exploratory Data Analysis

The EDA Dashboard provides visual insights into the dataset.

Genre Distribution

Understand the prevalence of movie genres.

Decade Analysis

Discover which decades dominate the collection.

Rating Distribution

Explore IMDb rating trends.

Director Analysis

Identify the most represented directors.

🖥️ Technologies Used

| Technology        | Purpose                   |
| ----------------- | ------------------------- |
| HTML5             | Structure                 |
| CSS3              | Styling                   |
| JavaScript (ES6)  | Recommendation Engine     |
| Chart.js          | Analytics & Visualization |
| TF-IDF Concepts   | Feature Weighting         |
| Cosine Similarity | Recommendation Logic      |

🚀 Getting Started

Clone Repository

```bash
git clone https://github.com/your-username/cinematheque.git

cd cinematheque
```

Run Locally

Simply open:

```bash
cinematheque.html
```

in any modern browser.

Or use:

```bash
python -m http.server
```

then visit:

```text
http://localhost:8000
```

📂 Project Structure

```text
Cinematheque/
│
├── cinematheque.html
│
├── assets/
│   ├── screenshots/
│   └── icons/
│
├── README.md
│
└── LICENSE
```
🎓 Educational Value

This project demonstrates:

* Recommender Systems
* Content-Based Filtering
* Information Retrieval
* Feature Engineering
* Similarity Search
* Data Visualization
* Frontend Machine Learning Concepts

Perfect for:

* Data Science Portfolios
* Machine Learning Projects
* Web Development Showcases
* Hackathons
* College Mini Projects

🌟 Future Enhancements

* Collaborative Filtering
* Hybrid Recommendation Engine
* User Accounts
* Movie Posters API Integration
* Watchlists
* Personalized Profiles
* Deep Learning Recommendations
* Natural Language Movie Search
* Sentiment-Based Recommendations

🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

"Cinema is a mirror by which we often see ourselves."

⭐ If you found this project useful, consider giving it a star on GitHub!
