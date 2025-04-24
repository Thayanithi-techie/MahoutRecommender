# 🧠 Mahout Recommender System

A simple **user-based collaborative filtering** recommender system built in **Java** using **Apache Mahout 0.9**.

This project reads user-item rating data from a CSV file and generates personalized product/content recommendations.

---

## 📌 Features

- User-based recommendation engine
- Pearson Correlation similarity
- Mahout 0.9 for collaborative filtering
- Console-based Java program
- Sample dataset included

---

## 📁 Files in this Project

MahoutRecommenderProject/ ├── src/ │ └── main/ │ └── java/ │ └── InternTask4/ │ └── RecommenderApp.java ← Main Java program ├── data.csv ← Sample user-item ratings ├── pom.xml ← Maven config file (optional)

---

## ▶️ How to Run This Project

### ✅ Option 1: Manual (No Maven)
1. Download these two JARs:
   - [mahout-core-0.9.jar](https://repo1.maven.org/maven2/org/apache/mahout/mahout-core/0.9/)
   - [slf4j-simple-1.7.25.jar](https://repo1.maven.org/maven2/org/slf4j/slf4j-simple/1.7.25/)
2. Open the project in Eclipse
3. Right-click project → **Build Path → Add External JARs**
4. Add both JARs
5. Run `RecommenderApp.java`

### ✅ Option 2: With Maven (if using pom.xml)
1. Make sure `pom.xml` is in your project
2. Run: mvn clean install
3. Then run `RecommenderApp.java`

---

## 📊 Sample Output

Recommended Item ID: 104 | Score: 4.12 Recommended Item ID: 105 | Score: 3.89

---

## 📝 Description

- Uses **user-based collaborative filtering**
- Measures similarity with **Pearson Correlation**
- Recommends top items for a given user (user ID 1 by default)

---

## 📧 Author

**Thayanithi** – built this for learning and demonstration purposes.

---

## 📃 License

Open-source, free to use!
