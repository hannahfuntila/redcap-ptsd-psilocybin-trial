# Veterans PTSD Psilocybin-Assisted Therapy - REDCap Database

## Project Note
This is an **educational portfolio project** demonstrating REDCap database design 
for a hypothetical psilocybin-assisted therapy trial in veterans with PTSD. 
All data shown is simulated test data.

## Project Overview
This REDCap project demonstrates:
- **Longitudinal study design** with 6 events (baseline through 3-month follow-up)
- **Safety monitoring** with conditional branching logic for adverse events
- **Clinical outcome measurement** using PCL-5 (PTSD Checklist for DSM-5)
- **Data validation** for vital signs and assessments
- **Calculated fields** for automated scoring

## Project Structure

### Main Project Files
- `VeteransPTSD_REDCap_Project.xml` - Complete project structure (import into REDCap)
- `Data_Dictionary.csv` - All fields with validation rules

### Blank Instrument Templates (01_BLANK_INSTRUMENTS/)
Templates showing what study participants see:
1. Baseline Demographics
2. Dosing Day Session
3. Safety Check-in
4. PTSD Followup Assessment

### Filled Examples (02_FILLED_EXAMPLES/)
Test subject (VET001) showing longitudinal outcomes:
- Baseline (PCL-5 = 58)
- Dosing Day Session
- Week 1 Follow-up (PCL-5 = 47)
- Month 3 Follow-up (PCL-5 = 32, clinical remission)

## Technical Skills Demonstrated
✓ REDCap longitudinal design with 6 events  
✓ Conditional branching logic for safety protocols  
✓ Repeating instruments for longitudinal assessments  
✓ Calculated fields for automated scoring  
✓ Data validation rules  
✓ Use of validated clinical outcome measures (PCL-5)  
✓ Clinical trial workflow understanding  

## How to Import This Project
1. Log into your REDCap instance
2. Create a new project
3. Select "Upload a REDCap project XML file"
4. Upload `VeteransPTSD_REDCap_Project.xml`
4. Review the structure
