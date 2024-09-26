# A3 - Intro to vegalite

---

**Due date:**

### Objective

In this assignment, you will produce visualizations, based on the `datasets/videogames_wide.csv` and `datasets/videogames_long.csv` datasets. They are the same datasets. But one of them makes your life easier. Pick the write one. You will use the vegalite library to produce visualizations.

There are three main parts:

- Describe the dataset
- Dreate visualizations and embed in your website
- Describe why your visualization choices were made.

### the dataset

The dataset is a collection of video game sales data with the following columns:

1. **Name**: The title of the video game.
2. **Platform**: The gaming platform on which the game was released (e.g., Wii, NES).
3. **Year**: The year the game was released.
4. **Genre**: The genre of the video game (e.g., Sports, Platform, Racing).
5. **Publisher**: The publisher of the game (e.g., Nintendo).
6. **NA_Sales**: Sales in North America (in millions of units).
7. **EU_Sales**: Sales in Europe (in millions of units).
8. **JP_Sales**: Sales in Japan (in millions of units).
9. **Other_Sales**: Sales in other regions (in millions of units).
10. **Global_Sales**: Total global sales (in millions of units).

### Part 1 - Describe the data

For each of the variables in the dataset, describe the `data type`, and provide summaries about each of them.

### Part 2 - Make 4 visual explorations with vegalite

- visualize global sales by genre and platform

  - what are the trends that you see? what's interesting?

- Visualize sales over time, by Platform, and genre

  - how have sales changed for these different genres, platforms, and publishers

- Visualize relationships between region sales and different platforms.

  - Are there patterns that you see that are interesting?

- Now that you have identified some patterns in the data, find something you find interesting. Tell a visual story about it.
  - I have left this intentionally vague. Anything goes, as long as you are using some of the lessons we have learned so far. An example is to focus on sales in the US region. Or just focusing on Playstation sales.

### Deliverables

You will make two submissions:

- You will then create your deliver your visualizations in your website using HTML, CSS, and JS. You can explore your data and make your visualizations in observable.

- Submit a PDF that describes your design choices. Based on the lectures we have had so far.

### Tips

There are some helper code provided for you in `index.html`, `style.css`, and `vis.js`. Feel free to ask questions and google how to do things.

### Resources

You can learn most things vegalite from this observable course [UW vegalite course](https://observablehq.com/@jonfroehlich/observable-tutorial?collection=@jonfroehlich/intro-to-vega-lite)

Another amazing [collection of lessons](https://observablehq.com/collection/@uwdata/visualization-curriculum)

Some vegalite-api examples can be found [here](https://observablehq.com/collection/@vega/vega-lite-api)
