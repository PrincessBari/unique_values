# unique_values

I had a file with 17,523 rows. I needed to see how many of the values in 
column "doc_name" were unique values.

I created a new dataframe df_4, which had 501 rows of unique values in the column
"first_number" and showed how many rows each value showed up in in the column
"count". 

By the end, I double-checked my math by totaling up everything in the "count" column
which equaled 17,433. I was also able to find that in the original dataframe df, there
were 90 rows in the column "doc_name" that had no numbers in the cells whatsoever. So
17,433 + 90 = 17,523. So all rows were accounted for
