# Accessing Data with Pandas

df = df.read_excel("score_results.csv")

`df / print(df) / display(df)`

#### To show the head

`df.head()`

#### To show the tail

`df.tail()`

#### To show the random data

`df.sample(11)`

> displays 11 radom rows but always different 11 random rows

#### To show the random data always same

`df.sample(11, random_state =1)`

> displays 11 radom rows but always same 11 random rows

*********************************************************************************************************************************************************************************

### .loc , .iloc


.loc is used for row names/ column names

.iloc is used for row index position and column position (numberical location)

df.loc[rows, columns]

df.iloc[rows, columns]





