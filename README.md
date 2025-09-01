## Computational Thinking Assignment – News Articles Analysis

This notebook was produced for a course assignment in Computational Thinking. The goal was to extract publication dates from raw text, transform them into weekly bins, and visualize article frequency.

The approach reflects how an applied economist would structure a problem:
* Decomposition → break down the task (extract → transform → visualize)
* Transformation → process raw data into structured information
* Visualization → communicate results clearly

It is not optimized for efficiency, but instead illustrates clear step-by-step logic and algorithmic thinking.
Problem-Solving Approach

1. Pattern recognition
   * Used regular expressions to identify publication dates in the raw text.
2. Mathematical transformation (key step)
   * Converted each date into its nth day of the year using datetime.
   * Mapped the day number into a week number using integer division.
   * This avoided inefficient list comparisons and showed how mathematical reasoning can simplify a data-processing task.
4. Counting & aggregation
   * Built a dictionary to count the number of articles per week.
5. Visualization
   * Created both a histogram (distribution of weekly frequencies) and a bar chart (weekly time series).

The key insight was recognizing that publication dates could be translated into simple numbers, making the problem much easier to solve.

Contents
* news-articles-analysis.ipynb: main notebook with code and explanations
* Histogram and bar chart of article frequencies per week (2022)
Tools
* Python (re, datetime, matplotlib)
* Jupyter Notebook
