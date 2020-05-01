# Course outline for Sentiment Analysis in R: The Tidy Way

## Chapter 1 – Basics of Sentiment Analysis
* Lesson 1.1 -Introduction to Sentiment Analysis
  * Learning objective: Learn what is Sentiment Analysis and what is a sentiment lexicon.
* Lesson 1.2 – The tidytext package
  * Learning objective: Introduction to the `tidytext` package, tokenizing text data, and tidytext (one-token-per-row). 
* Lesson 1.3 – Join, count, and visualize
  * Learning objective: How to combine `dplyr::inner_join()`, `dplyr::count()`, and ggplot2 to visualize sentiment.
  
## Chapter 2 – Sentiment Analysis Beyond the Basics
* Lesson 2.1 – Finding the right lexicon with `textdata`
  * Learning objective: Understand how sentiment is quantified and get a brief overview of different lexicons. 
* Lesson 2.2 – Potential Problems with Sentiment Analysis
  * Learning objective: Realize some of the limitations of this approach.
* Lesson 2.3 – Creating a custom lexicon
  * Learning objective: How to use `dplyr::bind_rows()` to create a custom lexicon. 
* Lesson 2.4 – Sentiment Analysis with `sentimentr`
  * Learning objective: How to use `sentimentr::get_sentences()` and `sentimentr::sentiment_by()` in a tidy way.

## Chapter 3 – More about Visualizing Sentiment Analysis
* Lesson 3.1 – Facet bar charts
  * Learning objective: Use `ggplot2::facet_wrap()` to make sense of your graphs.
* Lesson 3.2 – Scatterplots
  * Learning objective: Learn how to visualize sentiment data with a scatterplot.
* Lesson 3.3 – Word clouds
  * Learning objective: Use the `wordcloud` package to visualize your data.
* Lesson 3.4 - Sentiment changes over time
  * Learning objective: Learn how to analyze and plot sentiment over time.

## Chapter 4 – Case study: 80's Songs vs 90's Songs
* Lesson 4.1 - Step 1: Tokenizing and wrangling
  * Learning objective: Refresh your knowledge about tidytext and remove unwanted rows.
* Lesson 4.2 – Step 2: Join the right sentiment lexicon
  * Learning objective: Choose the right lexicon, join it, and count words.
* Lesson 4.3 – Step 3: Analyze Happy vs Sad songs
  * Learning objective: Use your knowledge to find differences between happy and sad songs.
* Lesson 4.4 – Step 4: Visualizing your data
  * Learning objective: Visualize yours results using the graphs you learned in the previous chapter.
  
