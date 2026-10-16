## 🔍 Key Findings

### 1. Ratings Are Uniformly Low
Across all 1,160 ratings in the dataset, the average overall rating is just 1.2 out of 2.0, a middling score that suggests most consumers found their dining experiences merely adequate. Even the top-rated restaurants, once filtered to those with at least five ratings, peak at an average of 2.0, and only a small handful of establishments such as Emilianos, Michiko Restaurant Japones, and Restaurant Las Mañanitas manage to sustain that level. The rest of the top five, including Cafe Punta Del Cielo and La Estrella De Dimas, sit just below at 1.83 and 1.80 respectively.

<img width="611" height="440" alt="Top 5 Rated Restaurants" src="https://github.com/user-attachments/assets/0ea3ce74-d902-49ca-99fc-aca96315dbe8" />

### 2. Price Does Not Predict Quality
A common assumption is that expensive restaurants deliver better experiences. This data says otherwise. Restaurants in the High price tier average 1.26, those in the Medium tier average 1.25, and those in the Low tier average 1.07. The gap between High and Medium is negligible at 0.01 points, and while Low-priced restaurants rate slightly lower, the difference is small enough that **price and rating are essentially uncorrelated** in this dataset.

<img width="611" height="440" alt="Restaurant Pricing vs Average Ratings" src="https://github.com/user-attachments/assets/a6b75988-f1a5-419a-88f1-1652cea8b85d" />

### 3. Location Matters
Restaurant ratings vary meaningfully by city. Cuernavaca leads with an average of 1.38, followed by Jiutepec at 1.25 and San Luis Potosí at 1.21. Ciudad Victoria trails significantly at just 0.93, despite having a comparable number of restaurants. This gap could reflect differences in restaurant quality, cuisine mix, or consumer expectations across cities, and it remains one of the more striking patterns in the data.

<img width="611" height="440" alt="City Restaurant Rating" src="https://github.com/user-attachments/assets/d5dfbf36-4f2e-4336-9007-e507fdba02c1" />

### 4. Alcohol Service Correlates with Satisfaction
Restaurants offering alcohol tend to receive better ratings, though the picture is more nuanced than "alcohol equals better." Restaurants with no alcohol service generate the most Highly Satisfactory ratings in absolute terms, but they also generate the most Unsatisfactory ones. Wine & Beer establishments show the healthiest ratio of highly-satisfactory to unsatisfactory ratings, suggesting a sweet spot for casual dining experiences, while Full Bar venues rate well but are far fewer in number.

<img width="611" height="440" alt="Alcohol Service by Rating Band" src="https://github.com/user-attachments/assets/08170448-560b-4422-99a1-cb5cde8905d0" />

### 5. Cuisine Preferences Are Heavily Skewed
Mexican cuisine dominates consumer preferences by a wide margin. Of all recorded preferences, 97 point to Mexican, while the next closest, American, has only 11. Cafeteria and Pizzeria tie at 9, and Coffee Shop follows at 8. This overwhelming skew reflects both the geographic concentration of the data and the cultural context of the restaurants analyzed. Any comparison of which cuisine is most popular quickly collapses into Mexican, and then everything else.

<img width="611" height="440" alt="Most Preferred Cuisines" src="https://github.com/user-attachments/assets/b2282794-014f-4f41-936c-b3425d0edbf1" />

### 6. Top-Rated Cuisines by Restaurant Rating
When we shift from consumer preference to restaurant quality, the picture changes. Mediterranean restaurants lead with an average rating of 1.75, followed by Coffee Shop at 1.58, Family at 1.57, International at 1.51, and Game at 1.43. Niche cuisines, in other words, tend to deliver more consistent quality than the mass-market options that dominate the preference rankings, a pattern worth noting for anyone thinking about where to open a restaurant.

<img width="611" height="440" alt="Top Rated Cuisines" src="https://github.com/user-attachments/assets/7c34e006-9d50-46c9-b03e-ababc83fbf38" />

### 7. Smoking Policies Vary Dramatically by City
Smoking policy is far from uniform across the four cities. San Luis Potosí is the most smoke-free at 96.77% non-smoking, followed by Cuernavaca at 88.24% and Ciudad Victoria at 82.61%. Jiutepec stands apart with a 50/50 split, a striking outlier, though one that likely reflects the small number of restaurants in that city rather than a genuine policy difference.

<img width="611" height="440" alt="Smoking Policy by City (%)" src="https://github.com/user-attachments/assets/80ad9ee3-e907-4bc2-8150-559aab53a080" />

### 8. Age Groups Show Similar Cuisine Patterns
Across every age bucket, Mexican cuisine dominates preferences. Consumers aged 18 to 25 account for 80 of the Mexican preferences, those aged 26 to 40 account for 10, and the 41 to 60 and 60+ buckets together account for just one. The dataset is heavily skewed toward younger consumers, which limits any meaningful comparison across age groups. The 60+ bucket in particular has virtually no data, a limitation of the dataset rather than a finding in itself.

<img width="611" height="440" alt="Age Group Cuisine Preference" src="https://github.com/user-attachments/assets/ea149bce-4f54-4d67-b459-6430d54b05b0" />

