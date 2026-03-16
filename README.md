# Information Retrieval Project Phase 1 (Text Parser)
# CSCE 5200 Information Retrieval and Web Search
# Done by: Sharmila Eday

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Structure
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project_Folder/
├── Parser_Output.txt           (The output text file generated)
├── Text_Parser_Phase_1.ipynb   (The code file for the text parser)
├── Porter_Stemmer.py           (Porter Stemmer code from the given Porter Stemmer document)
├── stopwordlist.txt            (The given stopword list)
├── ft911.zip                   (Zip folder containing ft911 documents)
└── README.md                   (This file)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Requirements
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Python 3.x (Google Colab)
- Built-in Python modules:
- re (regular expressions)
- zipfile (for reading the ft911 document zipfile)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
How to Run
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Open Google Colab and open the Text_Parser_Phase_1.ipynb file
2. Upload the following files: Porter_Stemmer.py, stopwordlist.txt, and ft911.zip
3. Run the code in the ipynb file
4. Output will be saved in the Parser_Output.txt file

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
What the program does
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1. This program is a text parser which parses the documents in the ft911 zip folder
2. It parses each document using tags
3. It tokenizes the text by splitting the words, removing numbers, and converting to lowercase
4. It Removes the stopwords from the given stopwordlist.txt
5. It Stems each word using the Porter_Stemmer.py file which has the Porter Stemmer function
6. It assigns a sorted alphabetical IDs to each of the unique words from the documents
7. It Assigns the IDs to each of the document to match with their FT911 - X number
8. Gives out the output to the Parser_Output.txt file
