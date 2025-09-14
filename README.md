# MacoraMachining

# MACORA Machining Performance Analysis

## Project Overview
Analysis of IoT telemetry data from MACORA Machining global manufacturing operations examining 160,704+ sensor records across four international facilities to identify operational patterns, equipment reliability trends, and performance optimization opportunities.

**Origin:** Extended analysis based on Deloitte Australia virtual internship dataset via Forage platform.

## Key Findings
- **Temperature Misconception**: No correlation found between operating temperature and machine failures (healthy: 25.0°C avg, unhealthy: 24.9°C avg)
- **80/20 Pattern Identified**: LaserWelders and LaserCutters account for 88% of all equipment failures despite representing only 22% of device types
- **Geographic Performance Gap**: Berlin facility outperforms Asian locations by 24:1 failure ratio (Berlin: 2 failures, Osaka: 48 failures)
- **Temporal Vulnerability**: Peak failures occur at 7:00 AM during morning startup procedures

## Business Impact
Analysis reveals specific operational blind spots and provides actionable recommendations for:
- Maintenance resource reallocation toward laser equipment
- Geographic best practice transfer from Berlin facility  
- Morning startup procedure optimization

## Technical Stack
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Analysis environment

## Repository Structure
├── MacoraManufacturingDataAnalytics.ipynb    # Main analysis notebook<br>
├── README.md                                  # Project documentation<br>
└── data/                                      # Data files (not included - see note below)

## Analysis Methodology
1. **Data Structure Assessment** - Examined dataset dimensions, data types, and nested JSON structure
2. **Feature Engineering** - Extracted hour, factory, temperature, and status from nested data
3. **Comparative Analysis** - Grouped healthy vs unhealthy equipment performance
4. **80/20 Analysis** - Identified device types contributing most to failures
5. **Geographic Performance Comparison** - Analyzed failure rates across factories
6. **Temporal Pattern Analysis** - Examined failure distribution by hour

## Key Questions Addressed
- What temperature ranges indicate healthy vs problematic operation?
- Which device types contribute most to operational failures?
- How do different facilities compare in operational performance?
- When do failures most commonly occur?
- What is the equipment reliability hierarchy?

## Data Note
Dataset originates from Deloitte Australia virtual internship program and is not included in this repository due to intellectual property considerations. Analysis methodology and findings are fully documented in the notebook.

## How to Run
1. Clone this repository
2. Install required packages: `pip install pandas jupyter`
3. Obtain dataset through Deloitte/Forage virtual internship program
4. Open `MacoraManufacturingDataAnalytics.ipynb` in Jupyter
5. Run cells sequentially

## Contact
https://www.linkedin.com/in/hamsini-a-kumar | hachyuthakumar@gmail.com

---
*This analysis demonstrates applied data analytics skills in manufacturing operations, combining statistical analysis with business intelligence to generate actionable operational insights.*
