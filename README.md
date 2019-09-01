# Course outline for Sentiment Analysis in R: The Tidy Way

## Chapter 1 – Basics of Text Mining
* Lesson 1.1 - Introduction to Text Mining
  * A learning objective: Learn that Sentiment Analysis is one of the many potential ways in which you could analyze text.
* Lesson 1.2 – The tidytext package
  * A learning objective: Short introduction to the `tidytext` package. 
* Lesson 1.3 – Tokenizing text
  * A learning objective: How to use `tidytext::unnest_tokens()` to tokenize text in a tidy way (one-token-per-row).

## Chapter 2 – Sentiment Analysis
* Lesson 2.1 – Quantifying the sentiment of text data
  * A learning objective: Understand how sentiment is actually quantified and get a brief overview of different lexicons (AFINN, bing, nrc).
 * Lesson 2.2 – Sentiment Analysis with tidytext
   * A learning objective: How to use `tidytext::get_sentiments()`
* Lesson 2.3 - Sentiment Analysis with sentimentr
  * A learning objective: How to use `sentimentr::get_sentences()` and `sentimentr::sentiment_by()` in a tidy way.
* Lesson 2.4 - Sentiment Analysis with `textdata`
  * A learning objective: Learn how to find the right datasource for your use case with `textdata`.

## Chapter 3 – Sentiment Analysis: The Tidy Way
* Lesson 3.1 – Using `dplyr`
  * A learning objective: Learn how to integrate sentiment analysis to your analytics pipeline using dplyr and pipes. 
* Lesson 3.2 – Joins and unions
  * A learning objective: Understand when and why you might want to use `inner_join`, `left_join`, `anti_join`, and `bind_rows`.
* Lesson 3.3 – Using `stringr`
  * A learning objective: Learn some `stringr` functions like `str_detect`, `str_extract`, or `str_replace` that might come handy.
* Lesson 3.4 – Using `ggplot2`
  * A learning objective: Pipe all of your work to `ggplot2` and get ready to start making graphs.

## Chapter 4 – Visualizing Sentiment Analysis
* Lesson 4.1 – Facet bar charts
  * A learning objective: Use `ggplot2::facet_wrap()` to make sense of your graphs.
* Lesson 4.2 – Scatterplots
  * A learning objective: Learn how to visualize your data using a scatterplot.
* Lesson 4.3 – Word clouds
  * A learning objective: Use the `wordcloud` package to visualize your data.
