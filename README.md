# ShoesFishAndTheLike
This copies the principle of BtrTaser, but for a simpler structure. 
That is, a collection of records in this case contains only 1 record type, in contrast to BTR and RAS (which each contain multiple types).

There are 2 components to this application:
The metadata which defines how to resolve the data, given the latter is a fixed field width-type file
The data

An example of metadata:
ShoeDefinition
Name            Offset Width Example (example not for use, just as illustration)
Id               1     10    63
Name            11     30    Kinky Boots
Manufacturer    41     12    Clarks
MinSize         53      2    3
MaxSize         55      2    13
CountryOfOrigin 57     30    Australia
EyeletCount     87      2    16
FishDefinition
Name            Offset Width Example
Id               1       8   34346
Comments         9      40   A thoroughly good egg
Name            49      30   Flounder   
BottomFeeder    79       1   Y
