Evaluating Health Equity in Sub-City Wastewater Monitoring of COVID-19 in Davis, California, Through an Assessment of Demographics

About the project

    Monitoring wastewater for severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2)—whether performed at a building, neighborhood, 
    or city level—has emerged as a viable way to track the prevalence of Coronavirus Disease-2019 (COVID-19) in a population. This study 
    assesses health equity implications for wastewater sampling paradigms at a sub-city (or sub-sewershed) scale. Many wastewater-based 
    disease surveillance efforts established during the COVID-19 pandemic relied on convenient points of access to sampling lcoations within 
    the sewer network and/or voluntary participation within a city or region. Sampling in this way may generate public health data that 
    does not equitably represent diverse populations within the area of interest. In preparation for future pandemics, better strategies 
    are needed to design wastewater sampling frameworks. We help address this knowledge gap by: (1) developing a geospatial analysis tool 
    that probabilistically assigns demographic data for subgroup populations aggregated by race and age (which were cited as major risk 
    factors for severe COVID-19 outcomes) from Census blocks to sub-sewershed sampling zones; (2) evaluating the representation of subgroup 
    populations and sub-sewershed wastewater data in Davis, California within the sampling framework employed for COVID-19 disease surveillance; 
    and (3) demonstrating a scenario planning strategy in which adaptive sampling prioritizes vulnerable populations (in this case, populations 
    >65 years old). Extensive sub-sewershed wastewater monitoring data was collected in Davis from November 2021 through September 2022, 
    with wastewater samples collected three times per week from 15 maintenance holes (nodes) and daily from the influent of the city’s 
    centralized wastewater treatment plant. The sub-city scale sampling achieved near complete coverage of the population, with spatial 
    resolution that informed public health communication initiatives within the city. Wastewater data aggregated from the sub-city scale 
    as a population-weighted mean correlated strongly with wastewater data collected from the centralized treatment plant (Spearman’s Rank 
    correlation coefficient 0.905). We considered four down-scaling scenarios for a reduction in the number of sampling zones from baseline 
    by 25% and 50%, chosen either randomly or by prioritizing maintenance of coverage for the >65-year-old population. Prioritizing 
    representation of this vulnerable population in zone selection increased coverage of >65-year-olds from 51.1% to 67.2% when removing 
    half of the sampling zones, while simultaneously increasing coverage of Black or African American populations from 67.5% to 76.7%. 
    Downscaling the number of sampling zones had little effect overall on the correlation between the sub-sewershed zone wastewater data 
    and centralized WWTP data (Spearman’s Rank correlations ranged from 0.875 to 0.917), but the strongest correlations were obtained when 
    maintaining sampling zones to maximize coverage of the >65-year-old population. When resource constraints necessitate downscaling the number 
    of sampling sites, the approach demonstrated herein can inform decisions in ways that help preserve spatial representation of 
    vulnerable populations, thereby promoting more inclusive, region-specific, and sustainable wastewater monitoring in the future.

Table of Contents

    adaptive_sampling_ex: Contains code related to scenario planning.

      baseline.ipynb: Performs probabilistic assignment under the baseline scenario conditions outlined in the adaptive sampling example (includes all sewershed nodes from this study). 
      scenario1.ipynb: Performs probabilistic assignment under the example scenario 1 conditions.
      scenario2.ipynb: Performs probabilistic assignment under the example scenario 2 conditions.
      scenario3.ipynb: Performs probabilistic assignment under the example scenario 3 conditions. 
      scenario4.ipynb: Performs probabilistic assignment under the example scenario 4 conditions.
      ww_scenarios.ipynb: Investigates how the aggregated wastewater signal is affected by each sampling regime modification.
      
    age_probabilistic_assignment.ipynb: Adapts the tool developed by Safford et al. (2022) to probabilistically assign demographic data (age) to sub-sewershed zones in Davis.
  
    files_to_import: Contains the datasets used in the study. Throughout each notebook file, there are instructions to “Insert the correct file directory here.” 
    Here, the file name in the code should correspond to the file present in this folder, though the directory will change depending on where you store the file.
  
	    tl_2020_06_tabblock20 is the 2020 Census block-level data. This file must be downloaded from Census.gov.
     
    race_probabilistic_assignment.ipynb: Adapts the tool developed by Safford et al. (2022) to probabilistically assign demographic data (race) to sub-sewershed zones in Davis.
  
    ww_surveillance.ipynb: Uses the Healthy Davis Together (HDT) wastewater surveillance data and considers how disease dynamics in sub-sewershed zones compare to overall city disease trends.
