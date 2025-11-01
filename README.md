# Spotify Emotions + Popularity Visual Analytics

*Data Visualization Course Project*

This project explores how **song popularity**, **genre**, and **emotions** interact in global Spotify charts using custom interactive visualizations built with **JavaScript + D3**.

We analyze >3 years of Spotify’s Daily Top 200 chart across **35 countries + Global** (2017–2020).

Dataset (Kaggle):
[https://www.kaggle.com/leonardopena/top50spotify2019](https://www.kaggle.com/leonardopena/top50spotify2019)

---

## What this project asks

* Are certain genres biased toward specific emotions?
* Do some emotions correlate with popularity?
* Do different countries emotionally “prefer” different genres?

---

## Visualizations

### 1) Genre → Emotion + Popularity (viz1.html)

Select a genre →

* **Radar chart** shows average emotion intensity for that genre
* **Bar plot** shows average popularity score

![viz1](https://user-images.githubusercontent.com/66360006/149676691-efc8a0b6-eb8c-4c08-aa3e-5d4bde5544e9.png)

### 2) Country → Emotion Distribution + Dominant Genre (viz2.html)

Select a country on the map →

* **Boxplots** show emotion distributions for that country
* Country color = **most popular genre**

![viz2](https://user-images.githubusercontent.com/66360006/149676708-68ce2555-46ee-4521-8685-92b11ae79f45.png)

### 3) Emotion → Top Songs Word Cloud (viz3.html)

Select an emotion →

* Word cloud of **Top 15 songs** for that emotion
* Color = genre
* Size = chart ranking
* Each title links directly to Spotify

![viz3](https://user-images.githubusercontent.com/66360006/149676715-41016ebf-b155-460b-84d3-1e892ce16d24.png)

### Home (home.html)

Landing page

![home](https://user-images.githubusercontent.com/66360006/149676730-bfa7a227-f5d3-4899-9731-151a395a1e30.png)

### About (about.html)

Short explanation of data + method

![about](https://user-images.githubusercontent.com/66360006/149676761-a57e14f2-408a-416d-8b8c-985c6a8395a0.png)

---

## Tech Stack

```
| Layer         | Technology                        |
| ------------- | --------------------------------- |
| Visualization | D3.js                             |
| Frontend      | HTML / CSS / JS                   |
| Data          | Spotify Daily 200 Charts (Kaggle) |
```

---
