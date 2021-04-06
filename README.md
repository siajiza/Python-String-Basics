<h1>Python-String-Basics - Introductory guide</h1>

Strings are a text data type made up of sequences of characters that represent and are interpreter as a text.

The Python interpreter has several built-in functions, related to strings text. 
To work correctly with Python´s strings and without any error, these interpreter needs to read everything of your code as the same data type, I mean, every data type must be interprete a text even the numbers or symbols must be read it like a text type.  

This strings - str() - are delimited among the uses of single or double quotes.

<h2>-EXAMPLE OF STRING AND THE USES OF THE QUOTES-</h2>

    my_year = 'This year 2021 will be my year!'

    type(my_year)
    <class 'str'>

    print(my_year)
    This year 2021 will be my year!

<h2>-SINGLE QUOTES AND DOUBLE QUOTES-</h2>

Some times, as while it can be used quotes as a principal declaration of string, as well we can need to use another quotes between of the content of the characters that are delimited whit anothers quotes. 
And then?... what would be able to be the problem or the contraposittion here?


<strong>Let´s see what to do but first let´s see an examples of the different cases.</strong>

The secret is don´t duplicate the same quotes among the string data type text. 


    sentence = 'The quick brown fox jumped over the lazy dog'

    sentence_two = 'That is my dog\'s bowl'   # Whit the use of this character _ dog\'s _ among the string data type text
                                              # only the principal quotes are reading by the interpreter of Python. 

    sentence_three = "That is my dog's bowl"  # We can combine the double and single quotes among the string data type text
                                              # and we don´t duplicate de quotes.

    sentence_four = "He said, \"is my dog\""  # Whit the use of this character _ \"is my dog\" _ among the string data type text
                                              # only the principal quotes are reading by the interpreter of Python. 







