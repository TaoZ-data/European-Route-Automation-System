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
1. Run the main Python script:
   ```
   python "EUROPEAN ROUTE AUTOMATION SYSTEM.py"
   ```
2. You can customize the countries and number of routes by editing the parameters in the script (see the `if __name__ == "__main__":` section).
3. When you run the script, all outputs (maps, timetables, reports) will be generated locally in an `outputs/` directory (which is not included in the repository).

## Project Structure
```
EUROPEAN ROUTE AUTOMATION SYSTEM/
├── EUROPEAN ROUTE AUTOMATION SYSTEM.py
├── requirements.txt
├── README.md
├── .gitignore
```

## Outputs Directory Structure
When you run the script, the following structure will be created in the `outputs/` directory:

```
outputs/
├── maps/           
│   ├── EUR_001_route_map.html
│   ├── EUR_002_route_map.html
│   └── ...
├── timetables/     # Excel file with all route timetables (one sheet per route)
│   └── all_timetables.xlsx
├── reports/        # Comprehensive analysis report (Excel)
│   └── european_route_analysis.xlsx
├── pricing/        # Pricing analysis (Excel)
│   └── european_pricing_analysis.xlsx
```

- **maps/**: Contains interactive HTML maps for each generated route.
- **timetables/**: Contains a single Excel file with all route timetables, each on a separate sheet.
- **reports/**: Contains a summary Excel report of all routes and cities analyzed.
- **pricing/**: Contains an Excel file with pricing analysis for each route.

## Notes
- The `outputs/` directory is not included in the repository and is generated locally when you run the script.
- If you want to share your results, you can manually upload the `outputs/` folder.

