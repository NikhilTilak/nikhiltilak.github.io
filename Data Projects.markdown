---
layout: page
title: Data Projects
permalink: /DS-projects/
order: 3
---

<p>I am also an avid programmer and a student of data science. I first became interested in Machine Learning techniques when I took part in the <a href="https://www.erdosinstitute.org/code">Erdos Institute Data Bootcamp</a> in 2020. My team <b>won first place out of twenty-six teams</b> in the final-project competition at the end of the bootcamp. </p>

<p>I have encorporated many of these techniques in my research. More recently I have dived into the world of Deep Learning by exploring datasets and notebooks on Kaggle and have even tried my hand at competitions. Check out some of my projects below! </p>

<h2>Sudoku Solver</h2>

Links: [GitHub repository](https://github.com/NikhilTilak/sudoku-solver), [App](https://sudoku-solver-2ik3k7t6qq-uk.a.run.app/)

<p float="center">
  <img src="../assets/dashapp032523.png" width="800" />
</p>

* Created an application to solve a Sudoku puzzle correctly given its image as input. 
*	Wrote a custom pipeline which processes the image, identifies the filled digits using OCR and a neural network and produces a solution. 
*	Deployed a Docker containerized Dash/Plotly app to Google Cloud (GCP).

<h2>Bookend- guess the author</h2>

Links: [GitHub repository](https://github.com/data-dart/bookend)

<iframe width="632" height="350" style="display: block; margin: auto;" src="https://www.youtube.com/embed/P1Sq7T9PvP0" title="bookend: a text classifier" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Trained an ensemble classifier model on books scraped from project Gutenberg which can predict the authorship of a snippet of text with a 93% accuracy.
* Led a team of four and was responsible for dividing tasks and establishing a GitHub-based workflow to maximize productivity.
* Extracted text features and implemented a bag-of-words model which gave the highest prediction accuracy score (85%) among the models considered.
* Presented the results to judges from industry and others in a short video format.
* Team won first place among twenty-six teams at the Erdos Institute Data Science Bootcamp (2020).

<h2>BreweryXplorer- explore breweries in the US</h2>

Links: [GitHub repository](https://github.com/NikhilTilak/BreweryExplorer), [Dashboard](https://brewxplorer2.herokuapp.com/)

<p float="center">
  <img src="../assets/brewxplorer.png" width="800" />
</p>

* Designed and deployed an interactive web app that lets users browse and search 3000+ breweries and pubs in the United States. 
* Scraped and cleaned unstructured brewery data gathered from Wikipedia and other web sources.
*	Designed an interactive Dashboard using Dash/Plotly which was deployed to Heroku.


<h2>IMDB movie reviews- good, bad or meh?</h2>
Links: [Kaggle kernel](https://www.kaggle.com/code/nikhiltilak/imdb-revs)

* The dataset from Kaggle contains 50,000 movie reviews labelled according to the sentiment.
* Trained a neural network to predict if a given movie review is “positive” or “negative”.
* Used a word2vec model trained on the reviews to generate semantic word embeddings which were used as features to a neural network.
* Model achieved 87% accuracy. 
* This can be used for sentiment analysis of other text data such as restaurant reviews, tweets, news articles etc.

