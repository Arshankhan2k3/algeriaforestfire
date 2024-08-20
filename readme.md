
---

# Algerian Forest Fire Prediction

## Overview
This project involves predicting forest fires in Algeria using weather data and various fire weather indices. The dataset includes observations from two regions in Algeria: the Bejaia region in the northeast and the Sidi Bel-Abbes region in the northwest, spanning from June 2012 to September 2012.

## Dataset Information
- **Total Instances**: 244 (122 instances for each region)
- **Time Period**: June 2012 - September 2012
- **Attributes**: 11 input attributes and 1 output attribute (class)
- **Classes**: Fire (138 instances) and Not Fire (106 instances)

### Attribute Information:
1. **Date**: (DD/MM/YYYY) - Observational date
2. **Temp**: Temperature at noon (°C) - Range: 22 to 42°C
3. **RH**: Relative Humidity (%) - Range: 21 to 90%
4. **Ws**: Wind Speed (km/h) - Range: 6 to 29 km/h
5. **Rain**: Total daily rainfall (mm) - Range: 0 to 16.8 mm

**FWI Components**:
6. **FFMC**: Fine Fuel Moisture Code - Range: 28.6 to 92.5
7. **DMC**: Duff Moisture Code - Range: 1.1 to 65.9
8. **DC**: Drought Code - Range: 7 to 220.4
9. **ISI**: Initial Spread Index - Range: 0 to 18.5
10. **BUI**: Buildup Index - Range: 1.1 to 68
11. **FWI**: Fire Weather Index - Range: 0 to 31.1

### Target Variable:
- **Classes**: Fire and Not Fire

## Project Requirements
- **Flask**
- **numpy**
- **pandas**
- **scikit-learn**

## Setup and Run Instructions

### 1. Clone the Repository
```bash
git clone [Your GitHub Repository URL]
cd [Your Project Directory]
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
- **Windows**:
  ```bash
  .\venv\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 4. Install the Required Packages
```bash
pip install -r requirements.txt
```

### 5. Run the Flask Application
```bash
python app.py
```

### 6. Access the Application
Open your web browser and navigate to `http://127.0.0.1:5000/` to access the application.

### 7. Deactivate the Virtual Environment (Optional)
When done, you can deactivate the virtual environment with:
```bash
deactivate
```

---
