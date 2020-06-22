# Nifi Flow - a simple template example
This template exemplifies the following steps:
1. Generate text files with content: [timestamp], [the second it was generated], [a random number between 0–99], [UUID]
2. Extract the seconds and the random number from the text.
3. Change the file name format based on the extracted properties: {the random number}-{seconds}-{UUID}.
4. Route the files based on the value of the random number (above or below 50).
5. Save the file into a directory. There are two directories: one for files equal or above 50, the other for files below 50.
