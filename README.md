# Messy_data_example_using_text_processing

For the followers of the course: Please respect your learning culture and do not copy the current code!

Each line of the `dates.txt` file corresponds to a single note. Each note has a date that needs to be extracted, but each date is encoded in one of many formats.

The goal is to correctly identify all of the different date variants encoded in this dataset and to properly normalize and sort the dates. 

With these rules, the correct date in each note will be recognized and returned as a pandas Series in chronological order.

For example if the original series was this:

    0    1999
    1    2010
    2    1978
    3    2015
    4    1985

The function should return this:

    0    2
    1    4
    2    0
    3    1
    4    3
