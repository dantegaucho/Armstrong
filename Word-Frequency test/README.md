#WORD FREQUENCY FILE

This file contains a python file *word_frequency.ipynb* 
*`create a function *main*` that accepts user input and use python function .split() and return the number of times words in the user input appears as output* 

def main():
  words = input("Enter text").split()

*`create an empty dictionary`*

word_frequencies = {}  

*`loop through each frequency of word`*

`for word in words:
     word_frequenciess[word] = word_frequencies.get(word, 0) +1
print(word_frequencies)

if __name__ == "__main__"
print(main)