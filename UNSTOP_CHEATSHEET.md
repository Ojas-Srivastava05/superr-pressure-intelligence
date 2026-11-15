# Unstop Submission Cheat Sheet — SupeRR Selector S2 Round 1

## Dropdowns — Top 10 Batters (Rank 1 → 10)

1. Yashasvi Jaiswal  
2. Suryakumar Yadav  
3. Liam Livingstone  
4. Naman Dhir  
5. Rovman Powell  
6. Shashank Singh  
7. Rajat Patidar  
8. Fakhar Zaman  
9. Ishan Kishan  
10. Namboori Tilak Varma  

*(If Unstop shows “Tilak Varma”, select that — data-pack display name is “Namboori Tilak Varma”.)*

## Dropdowns — Top 10 Bowlers (Rank 1 → 10)

1. Adam Zampa  
2. Sunil Narine  
3. Mitchell Santner  
4. Abrar Ahmed  
5. Rasikh Salam  
6. Rashid Khan  
7. Haris Rauf  
8. Adam Milne  
9. Mitchell Starc  
10. Akeal Hosein  

## Upload

- **Methodology report:** `outputs/final/SupeRR_Selector_S2_Pressure_Intelligence_Report.pdf`
- **Optional dashboard:** open `dashboard/index.html` via static host (see README)

## One-liner method

Pressure = within-innings P75 of √(Situation Strain × Match Leverage). Rank by composite of absolute pressure RAE (45%), baseline lift (25%), consistency (20%), confidence (10%), 75% IPL / 25% T20I, with bootstrap stability.
