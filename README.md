# enhanced-rock-weathering
Enhanced Rock Weathering Analysis using USGS Alaska Geochemical Database
Enhanced Rock Weathering Analysis.
📁 Project Structure
enhanced-rock-weathering/
├── ERW1.py                                                             # Main analysis script
├── Enhanced_Rock_Weathering_Analysis.png        # Visualization output
├── Enhanced_Rock_Weathering_Report.txt             # Technical report
├── README.md                                                       # Project documentation
├── data/                                                                   # Data directory
│ └── AGDB4_text/                                                    # USGS database files
│ ├── BV_WholeRock_Majors.txt
│ ├── Mineralogy.txt
│ └── Chem_A_Br.txt
└── requirements.txt                                                 # Python dependencies
A comprehensive geochemical modeling project for climate change mitigation through enhanced rock weathering, using real-world data from the USGS Alaska Geochemical Database.
🌍 Project Overview
This project demonstrates advanced geochemical modeling techniques to analyze the potential of Enhanced Rock Weathering (ERW) for CO₂ sequestration and agricultural applications. Using Python and PHREEQC integration, the analysis processes over 23,000 rock samples from Alaska to evaluate weathering potential, nutrient release, and carbon sequestration capabilities.
🎯 Key Features
•	Multi-component geochemical modelling using PHREEQC-Python integration
•	Real-world data analysis from USGS Alaska Geochemical Database (AGDB4)
•	Advanced visualization suite with 9-panel analysis dashboard
•	Climate impact assessment through CO₂ sequestration calculations
•	Agricultural potential evaluation via nutrient release analysis
•	Professional technical reporting with comprehensive documentation
 📊 Project Results
Sample 47818 Analysis Results:
pH Buffering: 5.60 → 8.00 (Δ = +2.40 pH units)
Total Cation Release: 1.01 mmol/L (Ca²⁺: 0.64, Mg²⁺: 0.37)
CO₂ Sequestration: 228.8 mg CO₂/L
Alkalinity Generation: 6.00 meq/L
Mineral Saturation: Calcite and Dolomite supersaturated
🔬 Technical Methodology
Data Source
Database: USGS Alaska Geochemical Database (AGDB4)
Sample Universe: 23,032 rock samples from Alaska, USA
Data Format: CSV files from AGDB4_text.zip
Source URL: https://www.sciencebase.gov/catalog/item/6500b2bed34ed30c2057f99b
Geochemical Modeling
Engine: PHREEQC v3.x with WATEQ4F thermodynamic database
Python Integration: PhreeqPy v0.6.0
Simulation Approach: Kinetic mineral dissolution with equilibrium precipitation
 Key Technologies
Python Libraries: pandas, matplotlib, numpy, phreeqpy
Geochemical Modeling: PHREEQC integration
Data Processing: Multi-dataset integration and preprocessing
Visualization: Advanced matplotlib plotting with scientific formatting
🚀 Installation & Setup
Prerequisites
 Python 3.7+
PHREEQC software (optional, fallback included)
 Git
 Installation Steps
1.Clone the repository
git clone https://github.com/yourusername/enhanced-rock-weathering.git
cd enhanced-rock-weathering.
2. Install dependencies.
pip install -r requirements.txt
3.Download USGS data
 Download AGDB4_text.zip from the USGS source
 Extract to `data/AGDB4_text/` directory
4. Run the analysis.
python ERW1.py
📋 Requirements
pandas
matplotlib
numpy
phreeqpy
🎨 Visualization Features
The analysis generates a comprehensive 9-panel visualization including:
1. pH Evolution - Acid neutralization capacity
2. Major Cation Release - Ca²⁺ and Mg²⁺ mobilization
3. Alkali Metal Release - Na⁺ and K⁺ for agricultural potential
4. Silicon Mobilization - Silicate weathering indicators
5. Carbon Sequestration - CO₂ capture potential
6. Mineral Saturation- Precipitation potential assessment
7. Cumulative Weathering - Total nutrient release
8. Weathering Efficiency - Performance metrics
9. Rock Composition- Major oxide distribution
🌱 Applications
Climate Change Mitigation
 CO₂ sequestration through enhanced weathering
 Carbon capture quantification
 Climate impact assessment
 Agricultural Enhancement
 Nutrient release analysis (Ca, Mg, K)
 Soil pH buffering capacity
 Sustainable agriculture applications
 Environmental Remediation
 Acid mine drainage treatment
 pH buffering for contaminated sites
Geochemical modeling validation
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
🙏 Acknowledgments
USGS for providing the Alaska Geochemical Database (AGDB4)
PHREEQC development team for geochemical modeling software
Scientific Python community for excellent libraries
📞 Contact
Author: Manadip  
Project: Enhanced Rock Weathering Analysis  
Date: May 2025  
This project showcases advanced technical skills in geochemical modeling, data science, and environmental applications.
