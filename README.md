# ENGR010-E1
# Imhotep’s Pyramid – Engineering Assignment 1

This project calculates the required materials to construct a pyramid inspired by Imhotep’s design. Using Python, the assignment walks through volume calculations, room sizing, stone requirements, and contingency planning.


## Objective
Compute:
- Total pyramid volume  
- Internal room volume  
- Stone‑occupied volume  
- Number of stones required  
- 10% contingency estimate  

All calculations follow engineering reasoning and use Python for accuracy.

## Workflow Summary

### 1. Total Pyramid Volume
- Base: 253.1 m × 253.1 m  
- Height: 147.2 m  
- Formula: \( V = \frac{1}{3} \times B \times H \)  
- Result: **3,143,191.53 m³**

### 2. Room Volume
- If volume > 1.5M m³ → room = 15%  
- Otherwise → room = 12%  
- Result: **471,478.73 m³**

### 3. Stone‑Occupied Volume
- Subtract room volume from total volume  
- Result: **2,671,712.80 m³**

### 4. Stone Requirements
- Stone volume: \(0.93^3\)  
- Exact stones needed: **3,321,551.00**  
- Whole stones to purchase: **3,321,552**

### 5. 10% Contingency
- Final stones required: **3,653,706.10**  
- Stones to purchase: **3,653,707**

## Key Findings
- Pyramid volume far exceeds the threshold, so the 15% room rule applies.
- Stone count must be rounded up for procurement.
- Contingency significantly increases required materials.

## Sources
- https://en.wikipedia.org/wiki/Imhotep  
- https://www.si.edu/spotlight/ancient-egypt/pyramid

