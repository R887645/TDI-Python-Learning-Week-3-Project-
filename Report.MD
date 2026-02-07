# Week 3: Data Structures & Supply Chain Network Understanding

In this Week 3 project, I moved beyond control flow and functions to focus on Python’s built-in data structures. This week was all about organizing and modeling the supply chain dataset using lists, dictionaries, sets, and nested structures.
![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Intro%20week%203.png?raw=true)

This experience made the dataset feel like a real network; suppliers connected to products, orders tied to costs, and warehouses linked to deliveries. It showed me how structuring data strategically reveals patterns and risks in supply chains.

---

## Key Skills Practiced

During this project, I strengthened my understanding of:

- Creating and manipulating **lists** for order values  
- Using list methods (`append`, `sort`) and calculating totals, averages, and medians  
- Building **dictionaries** to map products to suppliers and query relationships  
- Creating **sets** to find unique suppliers, products, and statuses  
- Identifying single-source products as supply chain risks  
- Constructing **nested data structures** (supplier → products → costs) to represent complex networks  
- Performing queries and aggregations on structured data  

---

## What I Implemented

### Order Analysis with Lists

- Extracted all `total_cost` values into a list  
- Calculated total, average, and median order values  
- Practiced sorting and indexing to analyze order distributions  
![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task%201A.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task%201B.png?raw=true)


### Product–Supplier Mapping with Dictionaries

- Built a dictionary mapping products → suppliers  
- Queried which supplier provides a specific product  
- Counted unique suppliers to understand network diversity 

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task2A.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task2B.png?raw=true)

### Unique Value Discovery with Sets

- Created sets for suppliers, products, and order statuses  
- Counted unique items in each category  
- Identified products supplied by only one supplier  

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task2c.png?raw=true)


### Risk Reporting

- Looped through product–supplier dictionary  
- Flagged single-source products as supply chain risks  
- Printed a clear risk report for stakeholders  

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Task%204.png?raw=true)

### Complex Network Modeling

- Built a nested structure mapping suppliers → products → costs  
- Queried products by supplier (e.g., “Show all products from Supplier A”)  
- Calculated total value of products per supplier  

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/task5A.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/task%205B.png?raw=true)


---

## Extra Challenges

- Filtered orders above a cost threshold and calculated their percentage of total orders  
- Found which supplier provides the most products  
- Grouped orders by status, queried delivered orders, and calculated their average value 

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Challenge%201A.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Challenge%201B.png?raw=true)


---

## Dataset Overview

The dataset contains thousands of rows with fields such as:

- `order_date`  
- `product_category`  
- `quantity`  
- `unit_price`  
- `total_cost`  
- `supplier_name`  
- `delivery_status` 

### Insights from Week 3 Analysis

- Multiple suppliers provide overlapping products, but some products are single-source risks  
- Order costs vary widely, with a few very high-value orders dominating totals  
- Delivery statuses show patterns that can be grouped and analyzed further 

[You Can view the Full week 3 project here](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/Week3_PersonalDataOrganizer%20(1).ipynb)

---

## Personal Challenges Faced but Overcomed

- Learning how to choose the most appropriate data structure (lists, dictionaries, or sets) for different analysis tasks

- Translating real-world supply chain relationships into properly structured Python code

- Debugging logic errors easily while working with nested data and complex queries


## Questions for Further Analysis

As I continue, I’m curious to explore:

- Which suppliers dominate in terms of both product variety and total value  
- How single-source risks impact overall supply chain resilience  
- Whether delivery delays correlate with specific suppliers or product categories  

---

## Reflection

This project was a turning point in learning how to structure real data. Lists, dictionaries, and sets moved beyond theory, they became tools to model relationships in the supply chain.

The most impactful part was building the nested supplier–product–cost network. It made the dataset feel alive, showing dependencies and risks clearly. I now see how analysts use Python not just to calculate, but to map and understand complex systems.

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-3-Project-/blob/main/conclusion%20wk%203.png?raw=true)

---

## Next Week

In Week 4, I’ll expand this work by learning file handling, data quality assessment, and cleaning the supply chain dataset to prepare it for deeper analysis.
