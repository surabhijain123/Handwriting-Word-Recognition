This code takes a png file as image of a 'singe word' and it is trained to give the text output of that word.
-> Requirements to execute this code are mentioned in 'requirements.txt' file. 
-> Image data tested is stored in 'tests' folder.
-> ../src/main.py This is the main file containing the code.
-> To test the code for another word, add the png file to the 'tests' folder and change the name of the file in 'main.py' line 19.
-> The program outputs the recognized text and the probability in console.
-> In addition, it stores the recognized word in '../src/output.txt'
-> Outputs obtained by testing till now are stored in the file 'output.txt'
-> Accuracy can be increased by implementing CTC Word Beam Search method. 

P.S.: This program is only trained for recognizing 'words' and not full sentence or paragraph.