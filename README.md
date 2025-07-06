# Dynamic-parking-pricing-summer-analytics
## capstone project

# Project Overview
This project simulates a real-time dynamic pricing engine for 14 urban parking lots, adapting prices based on:

1.Demand patterns  
2.Traffic conditions  
3.Special events  
4.Vehicle types  
5.Competitor prices  

# Architecture

graph TD
    A[Raw CSV Data] --> B[Data Preprocessing]
    B --> C1[ 1: Linear Pricing]
    B --> C2[ 2: Demand-Based Pricing]
    B --> C3[ 3: Competitive Pricing]
    
    C1 --> D[Real-Time pricing with Pathway]
    C2 --> D
    C3 --> D
    
    D --> E1[Live Updates]
    D --> E2[ Bokeh Visualization]

