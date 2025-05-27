# enhanced-rock-weathering
Enhanced Rock Weathering Analysis using USGS Alaska Geochemical Database
# Enhanced Rock Weathering Analysis

A comprehensive geochemical modeling project for climate change mitigation through enhanced rock weathering, using real-world data from the USGS Alaska Geochemical Database.

## 🌍 Project Overview

This project demonstrates advanced geochemical modeling techniques to analyze the potential of Enhanced Rock Weathering (ERW) for CO₂ sequestration and agricultural applications. Using Python and PHREEQC integration, the analysis processes over 23,000 rock samples from Alaska to evaluate weathering potential, nutrient release, and carbon sequestration capabilities.

## 🎯 Key Features

- **Multi-component geochemical modeling** using PHREEQC-Python integration
- **Real-world data analysis** from USGS Alaska Geochemical Database (AGDB4)
- **Advanced visualization suite** with 9-panel analysis dashboard
- **Climate impact assessment** through CO₂ sequestration calculations
- **Agricultural potential evaluation** via nutrient release analysis
- **Professional technical reporting** with comprehensive documentation

## 📊 Project Results

### Sample 47818 Analysis Results:
- **pH Buffering**: 5.60 → 8.00 (Δ = +2.40 pH units)
- **Total Cation Release**: 1.01 mmol/L (Ca²⁺: 0.64, Mg²⁺: 0.37)
- **CO₂ Sequestration**: 228.8 mg CO₂/L
- **Alkalinity Generation**: 6.00 meq/L
- **Mineral Saturation**: Calcite and Dolomite supersaturated

## 🔬 Technical Methodology

### Data Source
- **Database**: USGS Alaska Geochemical Database (AGDB4)
- **Sample Universe**: 23,032 rock samples from Alaska, USA
- **Data Format**: CSV files from AGDB4_text.zip
- **Source URL**: https://www.sciencebase.gov/catalog/item/6500b2bed34ed30c2057f99b

### Geochemical Modeling
- **Engine**: PHREEQC v3.x with WATEQ4F thermodynamic database
- **Python Integration**: PhreeqPy v0.6.0
- **Simulation Approach**: Kinetic mineral dissolution with equilibrium precipitation
- **Quality Control**: Multi-database fallback with synthetic validation

### Key Technologies
- **Python Libraries**: pandas, matplotlib, numpy, phreeqpy
- **Geochemical Modeling**: PHREEQC integration
- **Data Processing**: Multi-dataset integration and preprocessing
- **Visualization**: Advanced matplotlib plotting with scientific formatting

## 📁 Project Structure

