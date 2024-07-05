# UnrealExclusiveForLoop
Simple Blueprint Macro library with exclusive versions of the For Loop and For Loop with Break.
Removes the necessity of adding a "subtract 1" node whenever we don't want the last index iterated over (eg. if the input for "last index" is the length of an array, so the last index is n+1, meaning that iterating inclusively will cause an index out of bounds error).
