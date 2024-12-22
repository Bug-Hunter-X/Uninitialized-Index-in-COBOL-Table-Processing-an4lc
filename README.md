# Uninitialized Index in COBOL Table Processing
This example demonstrates a subtle error that can occur in COBOL when working with tables and indices. The issue lies in potentially accessing elements outside the defined bounds of the table if no check is provided. 

The provided COBOL program attempts to populate a table with string values. However, an error may occur if the `WS-INDEX` is not handled properly, and an attempt is made to access it after the table's upper bound is exceeded, or if the index is not properly initialized, leading to unpredictable results.