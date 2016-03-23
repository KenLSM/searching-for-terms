# searching-for-terms
Search for terms in another file

#Usage

    # file.txt
    lots of text but find me there
    not here
    but >there<
    
    # terms.txt
    there
    
    > python search.py file.txt terms.txt
    Found some lines containing: there
    lots of text but find me there
    but >there<
