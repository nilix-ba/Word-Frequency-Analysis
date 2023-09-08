# Word Frequency Analysis

This Python script performs word frequency analysis on text data stored in .txt files. It includes functions to:

1. **Load and Analyze Text Data**: The `inpt` function recursively searches a specified directory for .txt files and analyzes their word frequency.

2. **Text Preprocessing**: The `editor` function preprocesses text by converting it to lowercase and removing special characters, digits, and punctuation.

3. **Word Frequency Analysis**: The `analyze` function counts the frequency of each word in the text data, distinguishing between overall word count (`full_count`) and unique word count (`unique_count`).

4. **Heap's Law Visualization**: The `heap` function calculates Heap's Law parameters for the given data and visualizes the relationship between the logarithm of the total word count and the logarithm of unique word count using a linear regression model.

5. **Zipf's Law Visualization**: The `zipf` function calculates Zipf's Law parameters for the given data and visualizes the relationship between the logarithm of word rank and the logarithm of word frequency using a linear regression model.

The script initializes a global dictionary to store word frequencies, `full_count` to track overall word counts, and `unique_count` to track unique word counts. You can use this script to analyze text data from a specific directory by specifying the directory path in the `inpt` function call. After analyzing the data, it provides visualizations for Heap's Law and Zipf's Law, as well as a sorted word frequency dictionary.

**Usage**:

1. Ensure you have the necessary Python libraries installed (e.g., pandas, numpy, matplotlib, scipy).

2. Modify the `inpt` function call with the path to your directory containing .txt files.

3. Run the script to perform word frequency analysis and generate visualizations.
