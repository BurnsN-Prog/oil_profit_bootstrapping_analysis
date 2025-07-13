## Oil Region Profitability Analysis Using Bootstrapping

### Project Aim  
Help OilyGiant Mining Company determine the most profitable region to drill for oil using linear regression and bootstrapping techniques.

---

### Tools Used  
- Python  
- pandas, NumPy  
- scikit-learn (Linear Regression)  
- matplotlib  
- Bootstrapping 

---

### Results  
- **Region 2** had the lowest RMSE (**0.89**) in reserve volume prediction, but also the lowest average oil volume — **68.8k barrels**, below the break-even threshold.
- **Regions 1 and 3** had higher average predicted volumes (**92.5k** and **95k barrels** respectively) but worse model performance (RMSE ~**40**).
- Bootstrapping was used to simulate profit from the **top 200 predicted wells** per region.
- **Only one region** had a **< 2.5% risk of loss** while also delivering the **highest average profit**.
