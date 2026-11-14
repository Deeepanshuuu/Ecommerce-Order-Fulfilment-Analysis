# E-Commerce Order Fulfilment Analysis | Power BI & Lean Six Sigma (DMAIC)

## Project Overview

This project analyses e-commerce delivery performance and order fulfilment operations across Blinkit, Swiggy Instamart and JioMart.

Using Power BI and Lean Six Sigma's DMAIC framework, the analysis evaluates delivery performance, order accuracy, customer satisfaction indicators and operational inefficiencies.

The objective is to identify performance gaps, investigate potential operational problems and recommend data-driven improvements to enhance on-time delivery and order fulfilment accuracy.

## Business Problem

The analysis identified an on-time delivery (OTD) performance of **86%**, against a target range of 92–95%.

This indicates a 14% late-delivery rate across the analysed orders.

In addition to delivery delays, incorrect and missing items were identified as order fulfilment concerns, highlighting the importance of improving both delivery performance and order accuracy.

The project uses these findings to identify improvement opportunities across inventory handling, picking, packing and delivery operations.

## Project Objectives

- Evaluate overall order fulfilment and delivery performance.
- Measure on-time delivery and average delivery time.
- Analyse revenue and average order value across e-commerce platforms.
- Identify wrong and missing items as order accuracy concerns.
- Investigate potential operational issues using Root Cause Analysis.
- Apply the Lean Six Sigma DMAIC framework.
- Recommend practical improvements for delivery and fulfilment processes.

## Tools & Methodologies

| Category | Tools / Methodologies |
|---|---|
| Data Analysis & Visualization | Microsoft Power BI |
| Data Modelling & Calculations | DAX |
| Process Improvement | Lean Six Sigma |
| Problem-Solving Framework | DMAIC |
| Root Cause Analysis | Fishbone / Ishikawa Analysis |
| Operational Analysis | KPI Analysis |

## Key Performance Indicators (KPIs)

The project evaluates the following performance indicators:

| KPI | Result |
|---|---:|
| Total Revenue | ₹59 Million |
| Total Orders | 100,000 |
| Average Order Value | ₹590.99 |
| Average Delivery Time | 29.50 Minutes |
| On-Time Delivery (OTD) | 86% |
| Late Delivery Rate | 14% |
| Wrong Items Delivered | 7,738 |
| Missing Items in Orders | 7,737 |

### Platform Revenue Analysis

| Platform | Revenue |
|---|---:|
| Blinkit | ₹19.7 Million |
| Swiggy Instamart | ₹19.8 Million |
| JioMart | ₹19.6 Million |

## Dashboard Preview

The Power BI dashboard provides an overview of sales, order volume and delivery performance, supporting the identification of operational performance gaps.

### Dashboard Screenshots

Add your exported dashboard screenshots in the `Screenshots` folder and embed them below.

![Dashboard Overview](Screenshots/Overview.png)

![Delivery Performance Analysis](Screenshots/Delivery_Performance.png)

![Root Cause Analysis](Screenshots/Root_Cause_Analysis.png)

![Lean Six Sigma Improvement Framework](Screenshots/Improvement_Framework.png)

## Analysis & Key Findings

### 1. Delivery Performance

- Overall on-time delivery performance stands at 86%.
- 14% of deliveries fall outside the defined on-time delivery requirement.
- Average delivery time is approximately 29.50 minutes.
- The observed OTD performance is below the project's reference target of 92–95%.

### 2. Order Accuracy & Completeness

The analysis identified:

- 7,738 wrong items delivered.
- 7,737 missing items in orders.

These observations highlight potential weaknesses in inventory handling, picking and packing processes.

### 3. Root Cause Analysis

A Fishbone (Ishikawa) framework was used to explore potential contributors to delivery and fulfilment underperformance.

The investigation considered the following categories:

| Category | Potential Contributing Factors |
|---|---|
| People | Delivery partner-related factors |
| Process | Delivery routes, inventory handling and picking processes |
| Environment | Peak-hour demand and route congestion |
| Planning & Measurement | Demand planning and route optimization |
| Inventory & Materials | Inventory availability, picking and packing |

#### Evidence-Based Finding

The dataset recorded 7,738 wrong items and 7,737 missing items.

These observations identify inventory handling, particularly picking and packing, as an area requiring operational investigation.

#### Potential Causes Requiring Further Validation

Delivery route selection, traffic congestion, inventory shortages, demand forecasting and peak-hour order volumes were considered potential contributors to the 86% OTD performance.

However, these factors could not be independently established as root causes using the available dataset.

This distinction is important: the project separates observed evidence from hypotheses requiring further operational investigation.

## Lean Six Sigma – DMAIC Framework

The project applies the five stages of DMAIC to structure the improvement approach.

### 1. Define

**Problem:** On-time delivery performance is 86%, below the reference target of 92–95%.

**Objective:** Identify operational improvement opportunities to improve on-time delivery and order completeness.

### 2. Measure

The baseline performance was established using the available operational indicators:

- On-time delivery: 86%.
- Late delivery rate: 14%.
- Average delivery time: 29.50 minutes.
- Wrong items delivered: 7,738.
- Missing items in orders: 7,737.

These measurements establish the current performance baseline for improvement monitoring.

### 3. Analyze

Fishbone analysis was used to explore possible reasons behind delivery and fulfilment issues.

The strongest evidence-supported area for further investigation was inventory handling, particularly picking and packing, based on the recorded wrong and missing item counts.

Delivery route optimization and inventory availability were also identified as potential improvement areas, subject to further validation.

### 4. Improve

The following improvement strategies were proposed.

**A. Inventory Handling – Picking & Packing**

- Introduce barcode or product scanning during picking.
- Improve synchronization of the picking process.
- Establish a systematic picking sequence for bulk orders.
- Introduce a verification stage before packing and dispatch.

**Proposed process:**

`Pick → Verify → Pack → Dispatch`

The objective is to reduce incorrect and incomplete orders through better process control.

**B. Delivery & Logistics**

- Review delivery route selection.
- Explore route optimization.
- Identify potentially underperforming routes.
- Evaluate real-time delivery solutions where operational data supports their use.

**C. Pilot Implementation**

Rather than implementing changes across all operations immediately, the proposed approach is to:

1. Select affected SKUs for the inventory-handling pilot.
2. Select routes for delivery-related investigation.
3. Monitor baseline performance.
4. Measure performance after implementation.
5. Evaluate whether to adopt, modify or redesign the proposed improvements.

### 5. Control

The proposed control approach focuses on monitoring:

- On-Time Delivery.
- Late Delivery Rate.
- Average Delivery Time.
- Wrong Items.
- Missing Items.

Control charts and performance monitoring can help identify unusual variation and determine when corrective action is required.

## Expected Business Impact

The proposed improvements aim to deliver the following operational benefits:

| Area | Expected Impact |
|---|---|
| Order Accuracy | Fewer incorrect items |
| Order Completeness | Reduction in missing items |
| Delivery Performance | Improved on-time delivery |
| Inventory Handling | More standardized picking and packing |
| Logistics | Better route selection and delivery planning |
| Customer Experience | More reliable and complete deliveries |

**Note:** These are expected benefits of the proposed improvements, not measured post-implementation results. No completed pilot or verified before-and-after improvement figures are claimed in this project.

## Project Limitations

The available dataset supports analysis of delivery performance and order accuracy indicators, but does not independently establish every potential operational cause.

In particular:

- Route congestion and traffic conditions were not independently validated.
- Inventory shortage was considered a potential contributor but was not established as a confirmed cause of late deliveries.
- No post-implementation pilot results were available.
- Proposed improvements represent recommendations rather than verified operational outcomes.

## Repository Structure

```text
Ecommerce-Order-Fulfilment-Analysis/
│
├── README.md
│
├── Dashboard/
│   └── Order_Fulfilment_Analysis.pbix
│
├── Screenshots/
│   ├── Overview.png
│   ├── Delivery_Performance.png
│   ├── Root_Cause_Analysis.png
│   └── Improvement_Framework.png
│
└── Documentation/
    └── Lean_Six_Sigma_Analysis.pdf
```

## Key Takeaway

This project demonstrates the application of Power BI, DAX, operational KPI analysis and Lean Six Sigma problem-solving to evaluate e-commerce delivery and order fulfilment performance.

It combines performance measurement with structured root cause investigation and practical process improvement recommendations, demonstrating an analytical approach to supply chain and operations challenges.
