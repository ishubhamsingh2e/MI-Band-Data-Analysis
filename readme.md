<br/>

# Exploring Smart Band Data (MI BAND 5)

#### Test Subject:

- Gender: Male

- Height: 178cm

- Weight: 72kg

- BMI: 24.1

- Age: 20

by the way, this data is of my band 😁, so don't judge me.

### Activity

![](plots/steps/time_vs_distance_and_calorie.png)

The subject uses around **163.49-gram calories** (684.04216 Jules) in a day, equivalent to around **2 apples** [1].

maximum distance traveled by test subject is **15.411km(22558 steps)** in a day, ran **0.88km**, total calories burn over the day is **505**, on **2022-02-10**.

![](plots/steps/date_vs_calories.png)

consumption of calories over time is very unregular having a **MAD of 64.0** and **SD of 103.031**.

distance travel is quite stable having a **MAD of 1.83** and **SD of 3.09**.

### Activity Data Co-relation matrix

![](plots/steps/corr.png) ![](plots/steps/activity_boxplot.png)

I don't run much that's why it's like this.

In Activity data, less than 21% of data is extreme outliers.

### HistoGram

![](plots/steps/histo_steps.png) ![](plots/steps/histo_distance.png) ![](plots//steps/hist_calories.png)

**Steps ρ Distance ρ calories** shows similarity by which we can conclude they are highly  +vely correlated

##### skewness

- **Steps = 0.856**

- **Distance = 0.854**

- **Calories = 0.826**

## References

1. [Carbohydrate and Calorie Content of Foods By Item | MomsTeam](https://www.momsteam.com/nutrition/sports-nutrition-basics/nutritional-needs-guidelines/carbohydrate-and-calorie-content-of-foods)
