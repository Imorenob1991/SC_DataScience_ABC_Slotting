# SC_DataScience_ABC_Slotting

## Conceptual Analysis

The first topic we will analyze is ABC segmentation of sales, based on the Pareto Principle, also known as the 80/20 rule.

### About the Pareto Principle
The Pareto Principle, formulated by Vilfredo Pareto in 1896, states that 80% of outcomes are controlled by 20% of the factors. For example, 80% of total sales are generated by 20% of total products or SKUs.

### Application in Supply Chains

Common ABC Classification:

    - A Products: 20% of SKUs that generate 80% of total sales. These are usually referred to as fast-moving goods.
    
    - B Products: 30% of SKUs that generate 15% of total sales. These are usually referred to as medium/regular moving goods.
    
    - C Products: 50% of SKUs that generate 5% of total sales. These are usually referred to as slow-moving goods.

Before defining the type of products, it is important to sort the database from the product with the highest sales (first row) to the product with the lowest sales (last row) within a defined period of time (days, weeks, months, years).

The most common curve follows the 80:20 rule, but depending on the industry and strategy of each company, you might see different curves, such as 70:30 or 50:50. This is primarily affected by the type of industry and the assortment strategy.

## Graphical ABC Classification examples using the Pareto Principle

### 80:20 Example of ABC Classification

<img width="682" alt="Screenshot 2024-07-21 at 10 47 04" src="https://github.com/user-attachments/assets/a2e37843-4f8f-43f1-9b4d-d55924de9071">


Descriptive Analysis:
- Type A Product: 20% of SKUs represent the 80% of total sales and are fast moving goods.
- Type B Products: 30% of SKUs represent the 15% of total sales and are regular moving goods.
- Type C Products: 50% of SKUs represent the 5% of the total sales and are slow moving goods.

Insights and potential analysis:
  - Minimizing Picking Transit Time: Fast-moving goods or Type A Products should be stored in a location that minimizes picking transit time (warehouse or stores). This fast-moving goods     zone can vary depending on the layout.
  - Proximity to Clients: Type A Products have a high probability of being sold, so consider stocking them in a location closer to your clients to improve service levels.
  - Automation: This type of curve is suitable for Autostore Automation Goods-to-Person Technology, but consider other factors like logistics variables and the size of the products (Autostore is typically suitable for smaller items). AGVs (Automated Guided Vehicles) may also be applicable for this type of curve.

### 70:30 Example of ABC Classification

<img width="676" alt="70_30" src="https://github.com/user-attachments/assets/4a0f75ba-6bec-4dd4-b59d-34024cc628d3">

Descriptive Analysis:
- Type A Product: 30% of SKUs represent the 70% of total sales and are fast moving goods.
- Type B Products: 30% of SKUs represent the 20% of total sales and are regular moving goods.
- Type C Products: 40% of SKUs represent the 10% of the total sales and are slow moving goods.

Insights and potential analysis:
  - Minimizing Picking Transit Time: As with the 80:20 curve, Type A products are recommended to be stored in a zone that minimizes picking transit time.
  - Automation: Similar to the 80:20 curve, technologies like Autostore and AGVs (Goods-to-Person technology) can be considered for evaluation. However, this curve may make these technologies less competitive compared to traditional manual shelf picking. This is because the presentations per hour of the robots in these technologies decrease when the ABC curve is more spread.

### 50:50 Example of ABC Classification

<img width="675" alt="50_50" src="https://github.com/user-attachments/assets/07575a59-50fb-4171-9734-614f9514198d">

Descriptive Analysis:
- Type A Product: 50% of SKUs represent the 50% of sales.
- Type B Products: 30% of SKUs represent the 30% of sales.
- Type C Products: 20% of SKUs represent the 20% of sales.

This case is very particular, and we have two options:
  - All goods are slow-moving: The best strategy is to minimize investment in a manual solution (shelves or racks). Additionally, try to work with the marketing team to improve the rotation of goods with promotions or marketing campaigns.
  - All goods are fast-moving: If the size of the products is small, evaluate Goods-to-Person technology like Shuttles or prioritize high-rotation layout designs.
 
## Next Steps:

1. Create a project to define the ABC Classification curves that are recommended for each Goods to person techonoly and the reasons behind these assumptions:
     - Autostore
     - AGVs (Automated Guided Vehicules)
     - Shuttle.
     - Others.
  
2. Using real data from various industries, calculate the ABC curves and analyze any differences or similarities between them like:
    - Ecommerce.
    - Store Retail.
    - Whole Sales.
    - Automotive industry.
    - Others.
  
I hope you find this analysis and information useful. If you have any questions or comments, please don't hesitate to share them. I'm happy to discuss any specific questions you have and explore potential solutions or even create a new project to address them.















