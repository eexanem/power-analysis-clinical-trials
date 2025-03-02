# Power Analysis & Sampling Bias in Clinical Trials  

##  Overview  
This project simulates **statistical power analysis and sampling bias** for clinical trials and election polling. It investigates how **data accuracy and sample size** impact statistical estimates, focusing on oncology clinical trials.  

###  Key Features  
- **Statistical Power Analysis** using `pwr.p.test()`  
- **Monte Carlo Simulation** for estimating sampling bias  
- **Comparison of Small (Accurate) vs. Large (Error-Prone) Datasets**  
- **Visualization of Data Bias & Estimation Errors**  
- **Impact of Medical Data Errors** (misdiagnosis, incorrect treatment dates, missing records)  

##  Methodology  
1. **Simulated Data**: Generates synthetic clinical trial data with **varying accuracy levels (95% vs. 60%)**.  
2. **Power Calculation**: Determines sample size requirements for accurate drug utilization estimates.  
3. **Monte Carlo Simulation**: Evaluates how error rates (5% vs. 40%) affect statistical confidence.  
4. **Data Visualization**: Uses `ggplot2` to demonstrate how different datasets impact results.  

##  Requirements  
- R (latest version)  
- Packages: `pwr`, `simstudy`, `boot`, `ggplot2`, `dplyr`  

##  Running the Simulation  
1. Clone the repo:  
   ```sh
   git clone https://github.com/YOUR_USERNAME/power-analysis-clinical-trials.git  
   cd power-analysis-clinical-trials  
