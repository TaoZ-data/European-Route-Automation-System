# European Route Automation System

This project automatically discovers major cities in selected European countries, generates optimal bus routes between them, and creates professional documentation (maps, timetables, reports, and pricing analysis) for each route.

## Features
- Dynamic city discovery using OpenStreetMap and geocoding
- Intelligent route generation between cities
- Automated creation of maps and timetables
- Comprehensive Excel reports and pricing analysis
- All timetables are saved in a single Excel file with multiple sheets

## Requirements
- Python 3.7+
- See `requirements.txt` for required packages

## Installation
1. Clone this repository or download the files.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebook `EUROPEAN ROUTE AUTOMATION SYSTEM.ipynb`.
2. Run all cells from top to bottom.
3. You can customize the countries and number of routes by changing the parameters in the last cell, for example:
   ```python
   results = run_route_automation(['France', 'Germany'], 5)
   automation = CompleteDynamicAutomation()
   automation.generate_all_timetables(results['routes_data'])
   ```
4. All outputs (maps, timetables, reports) will be saved in the `outputs/` directory.

## Project Structure
```
EUROPEAN ROUTE AUTOMATION SYSTEM/
├── EUROPEAN ROUTE AUTOMATION SYSTEM.ipynb
├── requirements.txt
├── README.md
├── outputs/
│   ├── maps/
│   ├── timetables/
│   ├── pricing/
│   └── reports/
```

## Notes
- The first time you run the notebook, it may take a few minutes to fetch city data and generate outputs.
- If you want to share your results, you can upload the `outputs/` folder as well.

## License
This project is for educational purposes. 