# datafun-07-ML
datafun-07-ML: Explore supervised learning -- Linear Regression  

## Project Purpose
```
To implement the guided projects in 10.16 and 15.4 of textbook: Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud.
```

## Part 1: Chart a Straight Line
```
c = lambda f: 5 / 9 * (f - 32)
temps = [(f, c(f)) for f in range(0, 101, 10)]
temps_df = pd.DataFrame(temps, columns=['Fahrenheit', 'Celsius'])
axes = temps_df.plot(x='Fahrenheit', y='Celsius', style='.-')
y_label = axes.set_ylabel('Celsius')

```

## Part 2: Linear Regression Model using scipy
```
1. Data Acquisition 
2. Data Inspection
3. Data Cleaning
4. Descriptive Statistics
5. Build the Model
6. Predict
7. Visualizations
```

### Part 3: Linear Regression Model using scikit-learn
```
1. First, steps 1 to 4 will be the same as in Part 2
2. Build the Model
3. Predict
4. Visualization
```

### Part 4: Observe the differences between part 2 method and part 3 method
