## 🔸 Regression Discontinuity Design - COVID 🔸

## 🏆 Goal

Goal is to use RDD to estimate the effect of the following events in Quebec:

1. The 20/3/2020 lockdown
2. The reopening of schools on 31/8/2020
3. The 25/12/2020 lockdown.

## 📈 Data Source:
https://github.com/ccodwg/CovidTimelineCanada/tree/main/data/pt

The link provides all the data of Canada through out the timeline of the Covid.
We extracted all relevant data of Quebec starting January 23, 2020 until January 31, 2021 and combined them into one dataset.

## ☑️ Steps
The focus of our work is only on the daily Covid cases. We have also decided to make a window of 60 days because symptoms may appear 2-14 days after exposure to the virus.

<br>1. Extracted all the indices that contained the relevant dates needed.
<br>2. Assigned date as our independent variable (x) and daily cases as our dependent variable (y).
<br>3. Plotted the data in a scatter plot.
<br>4. Assigned a cutoff predictor.
<br>5. Added a new column named "day" as cardinal numbers to make it easier to plot and perform a regression on.
<br>6. Transformed the data and performed a Regression Discontinuity.
<br>7. Plotted the Final Regression Discontinuity Model.


## 📊 Results

### RDD March Lockdown.
![111](https://user-images.githubusercontent.com/39967400/210910200-12f871d3-aa4d-4d06-843f-353731c57644.png)

### RDD August Reopening
![image](https://user-images.githubusercontent.com/39967400/211121742-dbb911bc-45b1-4809-864a-c5846dd028be.png)

### RDD December Lockdown
![333](https://user-images.githubusercontent.com/39967400/210910344-6114f9d9-c1f6-4540-bfd1-3c15ed9cc731.png)



## ⭐ Conclusion
Our results show that both March and December lockdowns decreased the number of covid daily cases and August reopening increased the number of daily covid cases. We verified our models statistically with the significance of the cut off dates. 

## 🔸 Credits
[Mahmoud El Hazzouri](https://github.com/melhazzouri), [Amir Roshani](https://github.com/AmirRoshaniMoghaddam), [Sarb Choong](https://github.com/)

