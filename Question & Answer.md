# DEEP-LEARNING-PRACTISE
This will cover basics of Deep Learning & doubt sessions.


Important data Exploring Techniques.
Hue is available on Scatter, Box & Count Plot
df.corr()['price'].sort_values()
df.isnull().sum()
df.sort_values('price',ascending=False).head(20)
plt.figure(figsize=(12,8))
non_top_house = df.sort_values('price',ascending=False).iloc[16:] To remove top 15 houses.

CONVERT DATE INTO DATE TIME YEAR new Column.
df['date'] = pd.to_datetime(df['date'])
df['month'] = df['date'].apply(lambda date:date.month)
df['year'] = df['date'].apply(lambda date:date.year)


df.groupby('month').mean()['price'].plot()





KERAS PRACTISE BASIC
Questions are mentioned below.

1. Meaning of Conversion of Pandas to Numpy.
2. Need of scaling and transforming in Deep Learning for Lin. Reg Problem, however we don't scale and transform in Normal Linear Reg.
3. Why to fit X_train only, why not y_train?
4. Details on Sequential Modelling.
5. Why to use Deep learning if we can use Linear Reg/Logistic reg etc.
6. model.add(Dense(4,activation='relu')), why these 4 when we have 2 features only




Deep Learning for Linear Reg_Practise
Questions are mentioned below.
1.