# 🎬🎵 Simple Collaborative Filtering Recommendation System  

A **Python-based** recommendation system that suggests **movies** 🎥 and **music** 🎶 to users based on their shared preferences with other users.  

## 🚀 Features  
✅ **User-Based Collaborative Filtering** – Finds similar users based on shared ratings 👫  
✅ **Personalized Recommendations** – Suggests movies & music users haven't watched/listened to yet 🎧🎞️  
✅ **Dynamic & Expandable** – Easily add more users and ratings for better recommendations 📈  
✅ **Simple & Lightweight** – No external libraries, just pure Python 🐍  

## 📌 How It Works  
1. **User Ratings Dataset** 🎭  
   - Each user rates movies and songs on a scale of 1-5.  
2. **Finding Similar Users** 🤝  
   - Compares a target user’s ratings with others to find similar tastes.  
3. **Making Recommendations** 🏆  
   - Suggests items that similar users liked but the target user hasn't experienced yet.  
4. **Sorting by Interest Score** 🔢  
   - Recommendations are ranked based on the total ratings from similar users.  

## 🛠️ Code Overview  
```python
# Create an instance of the recommender system
collab_recommender = CollaborativeFilteringRecommender()

# Get recommendations for Alice
recommendations = collab_recommender.recommend_items("Alice")

# Display recommendations
for title, score in recommendations:
    print(f"{title} | Estimated Interest Score: {score}")
```

## 🏷️ Example Users & Ratings  
| User    | Movies & Songs Rated 🎶🎬 |
|---------|---------------------------|
| **Alice**   | Inception (5), Interstellar (4), Bohemian Rhapsody (2) |
| **Bob**     | The Dark Knight (5), Imagine (3), Inception (4) |
| **Charlie** | Avengers: Endgame (4), Hotel California (3) |
| **David**   | The Matrix (5), Billie Jean (5) |
| **Emma**    | Bohemian Rhapsody (5), Shape of You (4) |

## 📢 Future Enhancements  
🔹 Use **cosine similarity** for better user comparison 📊  
🔹 Integrate a **database** for dynamic user ratings 💾  
🔹 Implement a **graphical user interface (GUI)** for easy use 🎨  
🔹 Support **real-world datasets** from platforms like IMDb & Spotify 🌍  

---

### 🎯 Get Started  
🔹 Clone the repository  
🔹 Run the Python script  
🔹 Get personalized recommendations in seconds! 🚀  

---

👨‍💻 Developed as part of **CodSoft Internship – Task 4** 🎓  
Feel free to contribute & improve the system! 💡  
