# Breakout Session 2

## Banking

### Overview

We will sift through sample banking data from account holders and look at the distribution of funds. 

### Concepts

- Bucketing Data
- Applying ELK for Demographics

### Instructions

1. Import the banking data `account.json` with the `Machine Learning` `Data Visualizer` as you learned to do in Breakout Session 1.

![bank_import](assets/bank_import.PNG)

2. Click the `hamburger menu` and click `Visualize`

![visualize](assets/visualize.PNG)

3. Click `Create Visualization`

![create_viz](assets/create_viz.PNG)

4. Choose `Pie` for a pie chart

![pie](assets/pie.PNG)

5. Choose `banking` as your source index

![banking](assets/banking.PNG)

6. Click `+ Add` under `buckets` and choose `Split Slices'

![split_slices](assets/split_slices.PNG)

7. Choose `range` for your `Aggregation`

Enter the following ranges to split the slices.

![ranges_balances](assets/ranges_balances.PNG)

8. Extra credit: Add demographic data (challenge!)

![add_demo_data](assets/add_demo_data.PNG)
