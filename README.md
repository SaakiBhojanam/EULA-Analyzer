# EULA Analyzer

The **EULA Analyzer** is a web-based tool designed to help users understand the key aspects of an **End User License Agreement (EULA)**. It performs various text analysis tasks such as word count, readability score, sentiment detection, and generates a word cloud for EULA documents. This tool can help you break down complex legal language and gain insights into the contents of a license agreement.

## Features

- **Word Count**: Displays the total word count of the EULA text.
- **Unique Words**: Displays the count of unique words used in the document.
- **Readability Score**: Provides an average readability score based on sentence and word length.
- **Reading Level**: Estimates the reading level of the document (Elementary, Middle School, High School, College).
- **Estimated Reading Time**: Calculates the estimated time to read the EULA based on word count.
- **Longest Sentence**: Extracts the longest sentence in the EULA text.
- **Sentiment Analysis**: Detects legal-specific terms in the document to determine if the sentiment is more "Legal" or "Neutral".
- **Word Cloud**: Visualizes the most frequently used words in the EULA, excluding common stopwords.
- **Download Results**: Allows the user to download a report of the analysis in a `.txt` format.

## Demo

To see the tool in action, open the `index.html` file in your web browser.

## How to Use

1. **Paste your EULA text** into the provided text box.
2. Click the **"Analyze"** button to start the analysis. The tool will display the following results:
   - Word Count
   - Unique Words Count
   - Readability Score and Reading Level
   - Estimated Reading Time
   - Longest Sentence
   - Sentiment Analysis
   - A Word Cloud visualizing frequently used words.
3. You can download the analysis report by clicking the **"Download Results"** button, which will generate a `.txt` file.

## Technologies Used

- **HTML5**: Structure and layout of the webpage.
- **CSS3**: Styling of the page for an attractive and user-friendly design.
- **JavaScript**: Functionality for analyzing the EULA text, generating the word cloud, and exporting results.
  - **D3.js**: Used to create the word cloud.
  - **D3 Cloud**: A D3 plugin for rendering the word cloud.
