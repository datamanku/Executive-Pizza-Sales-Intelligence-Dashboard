
---

# Executive Pizza Sales Intelligence Dashboard

<img width="1033" height="650" alt="image" src="https://github.com/user-attachments/assets/2435b3ea-46fc-4555-b4e5-21d0f3fa0e38" />

---

## Purpose

This report was developed as a business intelligence solution to transform raw pizza sales transactions into a decision-support dashboard for leadership review.

The dashboard is designed to answer high-value business questions around:

- How core business KPIs can be tracked through a single executive view
- How sales are trending over time
- Which days and hours generate the highest demand
- Which pizzas are performing best and worst
- What customer preferences reveal about product category and size mix

This dashboard not just present information but rather frames operational and commercial performance using Power BI capability in executive reporting, KPI design, and decision-oriented analytics in a way that answer management questions, identify opportunities, and support better business decisions enabling better planning across staffing, inventory, promotions, and menu strategy.

---

## Business Problem

Restaurant and quick-service environments like pizza businesses generate large volumes of data every day and often track orders and sales at a transactional level. But leadership teams need a high-level consolidated analytical view to understand when demand peaks, which pizza drives revenue, and where menu or staffing decisions need adjustment in a way that supports business decisions. Hence  even though large volumes of transaction-level data are generated daily, decision-makers still struggle to make decisions because they often lack a consolidated view of performance.

Without a centralized dashboard, leadership teams struggled to answer questions such as:

- Are sales improving consistently over time?
- Which trading periods require stronger staffing and kitchen readiness?
- Which menu items are driving business performance?
- Which products may be underperforming and require review?
- What customer buying patterns should shape pricing, promotions, and stock planning?

This solution addresses that gap by creating an executive dashboard that converts raw order data into actionable business insights.

---

## Executive Questions

- What is the current topline performance snapshot leadership should review first? How do core KPIs summarize overall business health?
- Are we seeing consistent revenue momentum, stagnation, or seasonality across the year? How is sales performance trending month by month?
- Which days require stronger staffing coverage and higher operational readiness? Which days of the week experience the highest order volume?
- At what times is demand concentrated, and where should service capacity be optimized? During which hours does customer demand peak?
- Which menu items should be protected, promoted, repositioned, or reviewed for low contribution? Which pizzas are the strongest and weakest performers?
- Which product segments attract the most customer demand and deserve stronger focus? Which product categories are most preferred by customers?
- Which size mix drives customer choice, and how can packaging, pricing, and prep planning align? Which pizza sizes contribute most to order mix?


---



## Executive Business Insights

- KPI cards provide a compact executive summary for rapid business review.
- Monthly trend analysis supports revenue monitoring and helps identify periods of stronger or weaker commercial performance.
- Day-level demand analysis supports workforce planning and improves staffing alignment with customer traffic.
- Hour-level demand visibility helps operations teams prepare for service peaks and improve throughput readiness.
- Product performance ranking enables menu engineering by distinguishing hero items from weak contributors.
- Category and size preference analysis helps guide product positioning, promotional planning, and inventory preparation.


---



## Actionable Business Recommendations

Based on the dashboard structure, the following actions would be relevant for business stakeholders:

- Align staffing more closely with the busiest days and peak order hours
- Protect and promote top-performing pizzas through stronger menu placement or targeted offers
- Review bottom-performing products for repositioning, repricing, bundling, or removal
- Use category and size preference trends to optimize inventory planning and product mix
- Monitor monthly sales movement regularly to support proactive business planning


---


## Tools & Skills Used

- **Power BI**
- **Power Query**
- **Data Modeling**
- **DAX**
- **KPI Dashboard Design**
- **Business Performance Analysis**
- **Interactive Data Visualization**
- **Visual Story telling**


---

## Dataset
The project uses the Maven Analytics Pizza Place Sales dataset, consisting of four CSV tables:
- Orders
- Order Details
- Pizzas
- Pizza Types

Some of the many attributes that these tables capture are order timestamps, quantities, pizza attributes, category information, size, and item pricing.

---

## Data Preparation
Data preparation was performed in Power Query and included:
- Renaming tables and columns to improve reporting readability
- Promoting header rows where required
- Validating and correcting data types
- Reviewing column quality to confirm null-free fields
- Loading transformed tables into the Power BI data model

---

## Data Model

The report is built on a relational model where `Order Details` functions as the fact table and `Orders`, `Pizzas`, and `Pizza Types` serve as supporting dimension tables. A custom date table was created to enable month, quarter, weekday, and time-based analysis, improving reporting flexibility and supporting correct sort behavior for calendar attributes.

Additional calculated columns were created for:
- Time slots to identify peak ordering hours
- Month and month number for correct chronological sorting
- Day and weekday number for weekday trend analysis


- **Tables Relationships and Cardinalities**

<img width="1380" height="668" alt="image" src="https://github.com/user-attachments/assets/c3cee039-bdab-4b16-a6a8-ce16a5e3e31b" />




---


## Dashboard KPIs

The dashboard includes four primary KPI cards to provide an at-a-glance view of business performance:

- **Total Sales** – overall revenue generated

<img width="258" height="70" alt="image" src="https://github.com/user-attachments/assets/a4b0373f-5fac-453e-8765-0411f38517b9" />

- **Total Orders** – total volume of customer orders

<img width="248" height="67" alt="image" src="https://github.com/user-attachments/assets/623e51e2-24b6-47d1-9a2d-a9885db3222b" />

- **Average Orders per Day** – daily operational demand indicator

<img width="257" height="68" alt="image" src="https://github.com/user-attachments/assets/409dfd9a-c218-487e-8cff-f07fa884b635" />

- **Average Pizzas per Order** – basket-size / order composition indicator

<img width="252" height="68" alt="image" src="https://github.com/user-attachments/assets/dc8523ff-74eb-455c-98f2-036fad2bf5d5" />

These KPIs provide a leadership-level summary before drilling into more detailed analysis.


---




## Dashboard Design (Business Problem -> Analysis -> Insights & Recommendations -> Action)

### 1. Sales by Month

- **Business Questions**:  
How is the business performing over time, and are there visible periods of acceleration, slowdown, or seasonality?

<img width="488" height="239" alt="image" src="https://github.com/user-attachments/assets/82448f29-ee1c-4a22-9cdf-9360069e7ca0" />

- **Business Insights**:  
This view provides leadership with a time-based performance lens, enabling monthly tracking of revenue momentum and helping identify stronger and weaker trading periods for planning and review.

- **Executive Decisions**:  
Supports revenue monitoring, performance reviews, promotional timing, and forward planning.



### 2. Busy Days Analysis

- **Business Questions**:  
Which days generate the highest customer activity, and where should staffing and operational readiness be reinforced?

<img width="263" height="241" alt="image" src="https://github.com/user-attachments/assets/d3e749e3-55ec-4b00-8487-6de83196c11c" />

- **Business Insights**:  
This visual highlights demand concentration by day, helping management understand weekly order behavior and align labor coverage, prep activity, and service planning more effectively.

- **Executive Decisions**:  
Supports staff scheduling, shift planning, and service readiness optimization.



### 3. Peak Hours Analysis

- **Business Questions**:  
At what times of day is customer demand highest, and how should the business prepare for service pressure?

<img width="268" height="244" alt="image" src="https://github.com/user-attachments/assets/e6080b9d-0893-41a8-8eb0-3072517d0ba9" />

- **Business Insights**:  
Peak-hour analysis reveals when throughput pressure is greatest, creating visibility into the most operationally sensitive trading windows.

- **Executive Decisions**:  
Supports shift design, kitchen load preparation, and order-flow management.

### 4. Top 5 and Bottom 5 Pizzas

- **Business Questions**:  
Which menu items are driving performance, and which products may be weakening commercial efficiency?

<img width="487" height="283" alt="image" src="https://github.com/user-attachments/assets/23608cb7-ad91-4b56-8270-5d1d9769d9d8" />

- **Business Insights**:  
This ranking view distinguishes high-performing pizzas from low-contributing products, giving decision-makers a clear basis for menu engineering and commercial prioritization.

- **Executive Decisions**:  
Supports promotion strategy, product focus, bundling decisions, repricing, and underperforming menu review.



### 5. Preferred Category

- **Business Questions**:  
Which product categories are most aligned with customer demand?

<img width="263" height="260" alt="image" src="https://github.com/user-attachments/assets/1c060f3b-2b22-409a-b03b-1524279232a5" />

- **Business Insights**:  
Category preference analysis reveals where customer demand is concentrated across the menu, helping leadership understand which segments hold the strongest commercial pull.

- **Executive Decisions**:  
Supports campaign focus, menu design emphasis, and category-level inventory preparation.


### 6. Preferred Size

- **Business Questions**:  
Which pizza sizes dominate customer choice, and how should the business respond operationally and commercially?

<img width="269" height="255" alt="image" src="https://github.com/user-attachments/assets/3864c83f-54f3-42e8-aec5-7017d6570f68" />

- **Business Insights**:  
Size-mix visibility helps identify the most preferred product sizes, offering useful direction for packaging, pricing logic, stock allocation, and upsell strategy.

- **Executive Decisions**:  
Supports pricing decisions, packaging readiness, prep planning, and product mix strategy.

---

## DAX Used

The dashboard includes the use of calculated tables, columns and measures derived using DAX for the analysis purpose. 


- **Date Table**
  
<img width="677" height="825" alt="image" src="https://github.com/user-attachments/assets/d8cbea9f-ce23-4427-92f7-9a978370b6b5" />

- **Time Slot**

<img width="704" height="815" alt="image" src="https://github.com/user-attachments/assets/ffea62b7-1cf8-4312-b871-2abd14bca8ee" />

- **Time Slot Sorting**

<img width="696" height="830" alt="image" src="https://github.com/user-attachments/assets/05ab9b49-b279-4f3f-bacb-ee86dbe04744" />

- **Total Sales**
  
<img width="277" height="173" alt="image" src="https://github.com/user-attachments/assets/c23d291e-5058-44f5-9b5d-b7633db2e406" />

- **Total Orders** 

<img width="293" height="67" alt="image" src="https://github.com/user-attachments/assets/e28019d4-3ecf-4ffc-84af-6019be617671" />

- **Average Orders per Day** 

<img width="400" height="128" alt="image" src="https://github.com/user-attachments/assets/43e416c3-e328-4de7-92f7-d9e655301b8b" />

- **Average Pizzas per Order**
  
<img width="473" height="135" alt="image" src="https://github.com/user-attachments/assets/d6ceb763-b803-40c2-83b8-7b9c90771d8f" />


These Dax functions helps in providing the base for drilling into more structured, detailed and specific analysis directed towards problem statement at hand.



---


## Business Value Delivered

This dashboard utilizes Power BI capabilities to move beyond descriptive reporting and support executive decision-making by answering real world business questions.

The solution helps frame key operational and commercial questions in a visual, business-friendly format and provides insight into:

- Revenue performance
- Demand timing
- Product performance
- Customer preference patterns
- Operational planning opportunities

Overall, this showcases how business intelligence can turn transactional data into strategic visibility creating value for money.

---


---


