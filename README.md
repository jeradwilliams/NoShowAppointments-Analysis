# No-Show Medical Appointments Analysis  
**Brazil 2016 - ~110k appointments**

Project analyzing factors associated with patients missing scheduled medical appointments (no-show behavior).

## Key Findings
- **Waiting time** is the strongest single predictor: >30 days -> >30% no-show rate  
- Young adults (15-35 years) with long waits and **no SMS reminder** show the highest risk (~34%)  
- SMS reminders appear helpful especially for longer waiting times  
- Patients enrolled in Bolsa Família (scholarship) tend to have modestly higher no-show rates  
- Significant variation exists across neighbourhoods

## Tools & Techniques
- Python · pandas · numpy  
- matplotlib · seaborn  
- Feature engineering (waiting days, age groups, chronic condition flag)  
- Distribution analysis, outlier handling, descriptive statistics  
- Reusable plotting function for consistency

## Files in this repository
- `NoShow_Analysis_Final.ipynb`     → complete Jupyter notebook  
- `NoShow_Analysis_Final.pdf`       → exported report  
- `noshowappointments-kagglev2-may-2016.csv` → original dataset (optional upload)

## Author
Jerad Williams

[View PDF Report](NoShow_Analysis_Final.pdf)

---

⭐ Feel free to star / fork if this was helpful!
