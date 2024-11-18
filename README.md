# Text Analysis Assignment

## Objective
The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables that are explained below.

## Data Extraction

### Input File: `Input.xlsx`
For each of the articles given in the `Input.xlsx` file:
- Extract the article text and save the extracted article in a text file with `URL_ID` as its file name.
- When extracting text, ensure that only the **article title** and **article text** are extracted. 
- Avoid extracting the website header, footer, or any other non-article content.

## Data Analysis

For each of the extracted texts from the articles, perform textual analysis and compute the variables specified in the **Output Data Structure** file (`Output Data Structure.xlsx`).

The results should be saved in the exact order as given in the **Output Data Structure.xlsx** file.

## Variables to be Computed

The following variables need to be computed based on the analysis document `Text Analysis.docx`:

1. **POSITIVE SCORE**
2. **NEGATIVE SCORE**
3. **POLARITY SCORE**
4. **SUBJECTIVITY SCORE**
5. **AVG SENTENCE LENGTH**
6. **PERCENTAGE OF COMPLEX WORDS**
7. **FOG INDEX**
8. **AVG NUMBER OF WORDS PER SENTENCE**
9. **COMPLEX WORD COUNT**
10. **WORD COUNT**
11. **SYLLABLE PER WORD**
12. **PERSONAL PRONOUNS**
13. **AVG WORD LENGTH**

## Output Data Structure

### Output Variables:
1. All input variables from `Input.xlsx`.
2. **POSITIVE SCORE**
3. **NEGATIVE SCORE**
4. **POLARITY SCORE**
5. **SUBJECTIVITY SCORE**
6. **AVG SENTENCE LENGTH**
7. **PERCENTAGE OF COMPLEX WORDS**
8. **FOG INDEX**
9. **AVG NUMBER OF WORDS PER SENTENCE**
10. **COMPLEX WORD COUNT**
11. **WORD COUNT**
12. **SYLLABLE PER WORD**
13. **PERSONAL PRONOUNS**
14. **AVG WORD LENGTH**

Please refer to the `Output Data Structure.xlsx` file for the format of your output.

---

### Files Provided:
- `Input.xlsx`: Contains a list of articles with their URLs.
- `Text Analysis.docx`: Contains a detailed description of the variables to compute.
- `Output Data Structure.xlsx`: Contains the required output format.

---

## Instructions:
1. Extract the text from the articles using the provided URLs in the `Input.xlsx` file.
2. Perform text analysis and compute the specified variables.
3. Save the computed values in the same order as shown in the `Output Data Structure.xlsx` file.
4. Ensure that your program correctly handles the extraction and analysis steps for all articles.

---

## Notes:
- Make sure your program handles the extraction of the article text correctly, ignoring any extraneous website content.
- Follow the format of the output spreadsheet exactly as required.

