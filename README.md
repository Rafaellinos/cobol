case insensitive


# Basics

1 to 6 : Sequence number area | 
7 = indicator area | *  d \
8 to 11 = A area | division
12 to 72 = B area | statement, setences, etc
73 to 80 = identificator area | ignored by compiler


division -> sections -> paragraphs -> sentences -> statements

division = Author, enviroment, data division (memory, storage), precedure

paragraphs = like funcions, can call somewhere

IF ITEM = "B"
    ADD 2 TO TOTAL
END-IF

sentence = ADD 2 TO TOTAL.
statements = ADD, TO, .

DOT = ending

# Variables

Picture = length of variable
PIC 9 = single numeric value, length one
9 means numeric
PIC 9(4) = length numeric of 4. 9999
PIC A = single character alphabethic
PIC X(8) = letters and numbers

PIC 9(4)V99 = MAX 9999,99
PIC $9,999V99 = 

PIC x(32) VALUE SPACES = String(" " * 32)

# Data division

# keywords

MOVE = moves data into a variable

```cobol
SOME-VARIABLE PIC X(32).
SOME-NUMBER PIC 9(1)
MOVE "Some String" TO SOME-VARIABLE.
COMPUTE RESULT = SOME-NUMBER * SOME-NUMBER.
```

