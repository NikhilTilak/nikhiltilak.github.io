---
layout: page
title: Data Projects
permalink: /DS-projects/
order: 3
---

<h2>Sudoku Solver</h2>

Links: [GitHub repository](https://github.com/NikhilTilak/sudoku-solver)

<p float="center">
  <img src="../assets/solver_v1.jpg" width="800" />
</p>

* Solve a Sudoku puzzle correctly given an image.
* A custom image processing pipeline splits the Sudoku into one image per cell (81 images total).
* A neural network trained on images of printed digits, then identifies the filled in digits and generates a sudoku object.
* The Sudoku is then solved using a straightforward algorithm.
* version 2 can take as input images of printed Sudokus taken with a phone which can be at an arbitrary angle.

<h2>Bookend</h2>

Links: [GitHub repository](https://github.com/data-dart/bookend), [App](https://bookend-data-dart.herokuapp.com/)

<iframe width="632" height="350" src="https://www.youtube.com/embed/P1Sq7T9PvP0" title="bookend: a text classifier" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Trained an ensemble classifier model on books scraped from project Gutenberg which can predict the authorship of a snippet of text with a 93% accuracy.
* Led a team of four and was responsible for dividing tasks and establishing a GitHub-based workflow to maximize productivity.
* Extracted text features and implemented a bag-of-words model which gave the highest prediction accuracy score (85%) among the models considered.
* Presented the results to judges from industry and others in a short video format.
* Team won first place among twenty-six teams at the Erdos Institute Data Science Bootcamp (2020).


<h2>IMDB movie reviews sentiment analysis</h2>
Links: [Kaggle kernel](https://www.kaggle.com/code/nikhiltilak/imdb-revs)

* The dataset from Kaggle contains 50,000 movie reviews labelled according to the sentiment.
* Trained a neural network to predict if a given movie review is “positive” or “negative”.
* Used a word2vec model trained on the reviews to generate word embeddings.
* Model achieved 87% accuracy. 
* This can be used for sentiment analysis of other text data such as restaurant reviews, tweets, news articles etc.

<h2>BreweryXplorer</h2>

Links: [GitHub repository](https://github.com/NikhilTilak/BreweryExplorer), [Dashboard](https://brewxplorer2.herokuapp.com/)

<p float="center">
  <img src="../assets/brewxplorer.png" width="800" />
</p>

* Browse and search 3000+ breweries and pubs in the Unites States.
* Scraped and cleaned unstructured brewery data gathered from Wikipedia and other sources.
* Designed an interactive Dashboard using Dash/Plotly which was deployed to Heroku.
