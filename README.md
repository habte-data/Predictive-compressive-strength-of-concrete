# **Predictive Compressive Strength of Concrete**  

## **Project Overview**  
This project focuses on predicting the **compressive strength of concrete** using machine learning techniques. The dataset consists of various **concrete mix components** and their influence on the final compressive strength.  

## **Dataset Information**  
- **Source:** Concrete Strength Dataset  
- **Number of Samples:** (Update with `df.shape`)  
- **Number of Features:** 9  
- **Target Variable:** `concrete_strength` (Compressive Strength in MPa)  

## **Column Renaming**  
To improve readability and consistency, the dataset column names were renamed as follows:  

| Original Column Name | New Column Name |  
|-----------------------------------------------|--------------------|  
| Cement (component 1)(kg in a m³ mixture) | `cement` |  
| Blast Furnace Slag (component 2)(kg in a m³ mixture) | `blast_furnace_slag` |  
| Fly Ash (component 3)(kg in a m³ mixture) | `fly_ash` |  
| Water (component 4)(kg in a m³ mixture) | `water` |  
| Superplasticizer (component 5)(kg in a m³ mixture) | `superplasticizer` |  
| Coarse Aggregate (component 6)(kg in a m³ mixture) | `coarse_aggregate` |  
| Fine Aggregate (component 7)(kg in a m³ mixture) | `fine_aggregate` |  
| Age (day) | `age` |  
| Concrete compressive strength (MPa, megapascals) | `concrete_strength` |  
