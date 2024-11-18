# StangAllen_SJGIPaper

Namelists, postprocessing and analysis scripts for "Seasonably variable estuarine exchange through inter-connected channels in the Salish Sea" 

[![DOI](https://zenodo.org/badge/889264419.svg)](https://doi.org/10.5281/zenodo.14182582)

### Ariane Runs ###

Namelists in directory Namelists see subdirectory names below.

From Victoria Sill to Haro, Rosario, SJC (also to Admiralty and Deception) 
   - Name in Table 1: Split1F
   - Directory: forVS_split

To Victoria Sill from Haro, Rosario, SJC (also from Admiralty and Deception)
   - Name in Table 1: Split1B
   - Directory: backVS_split

From Point Roberts to Haro, Rosario, SJC (also to Gulf Islands)
   - Name in Table 1: Split2F
   - Directory: forPR_split

To Point Roberts from Haro, Rosario, SJC (also from Gulf Islands)
   - Name in Table 1: Split2B
   - Directory: backPR_split

From Victoria Sill through Haro Strait
   - Name in Table 1: Full1F_haro
   - Directory: forVS_haro

From Point Roberts through Haro Strait
   - Name in Table 1: Full2F_haro
   - Directory: forPR_haro

From Admiralty Inlet through Haro Strait
   - Name in Table 1: Full3F_haro
   - Directory: foradm_haro

From Gulf Islands through Haro Strait
   - Name in Table 1: Full4F_haro
   - Directory: forgulf_haro

From Victoria Sill through Rosario Strait
   - Name in Table 1: Full1F_ros
   - Directory: forVS_ros

From Point Roberts through Rosario Strait
   - Name in Table 1: Full2F_ros
   - Directory: forPR_ros

From Admiralty Inlet through Rosario Strait
   - Name in Table 1: Full3F_ros
   - Directory: foradm_ros

From Gulf Islands through Rosario Strait
   - Name in Table 1: Full4F_ros
   - Directory: forgulf_ros

From Victoria Sill through San Juan Channel
   - Name in Table 1: Full1F_sjc
   - Directory: forVS_sjc

From Point Roberts through San Juan Channel
   - Name in Table 1: Full2F_sjc
   - Directory: forPR_sjc

From Admiralty Inlet through San Juan Channel
   - Name in Table 1: Full3F_sjc
   - Directory: foradm_sjc

From Gulf Islands through San Juan Channel
   - Name in Table 1: Full4F_sjc
   - Directory: forgulf_sjc

To Victoria Sill through Haro Strait
   - Name in Table 1: Full1B_haro
   - Directory: backVS_haro

To Point Roberts through Haro Strait
   - Name in Table 1: Full2B_haro
   - Directory: backPR_haro

To Admiralty Inlet through Haro Strait
   - Name in Table 1: Full3B_haro
   - Directory: backadm_haro

To Gulf Islands through Haro Strait
   - Name in Table 1: Full4B_haro
   - Directory: backgulf_haro

To Victoria Sill through Rosario Strait
   - Name in Table 1: Full1B_ros
   - Directory: backVS_ros

To Admiralty Inlet through Rosario Strait
   - Name in Table 1: Full3B_ros
   - Directory: backadm_ros

To Victoria Sill through San Juan Channel
   - Name in Table 1: Full1B_sjc
   - Directory: backVS_sjc

To Admiralty Inlet through San Juan Channel
   - Name in Table 1: Full3B_sjc
   - Directory: backadm_sjc

### Data Processing ###

calculate_balances_avg.ipynb: Calculates monthly averages of the transport moving into and out of the SJGI region and calculates the transport moving through each of Haro Strait, Rosario Strait, and San Juan Channel.

CalculateTimeSeries_ThroughHaro.ipynb/CalculateTimeSeries_ThroughRosario.ipynb/CalculateTimeSeries_ThroughSJC.ipynb/Get_Shifted_Transport.ipynb: Extracts the transport data from Ariane runs and shifts forward/backward runs to match timing. Combines the transport data from into a time series and saves to csv.

CalculateMonthlyAvgs: Combines data from Ariane files, caculates the monthly average for transport, salinity, temperature and saves to csv files.

reflux_SJI_analysis.ipynb: Calculates transport and salt flux associated with reflux, efflux, tidal sloshing through the SJGI.

Calculate_Wind.ipynb: Calculates the wind at Sand Heads and shifts to match the along strait and across strait direction of SalishSeaCast.

Calculate_IntegDens.ipynb: Calculates the density difference between 2 points through the SJGI region.

Calculate_Tides.ipynb: Calculates the tidal velocity squared in Boundary Pass.

Calculate_PugetRivers.ipynb: Calculates the river flux into Puget Sound.

### Figures ###

Figure 1: maps_sjgi.ipynb

Figure 2: ModelEval_SJGI.ipynb

Figure 3: Monthly_CrossSections.ipynb

Figure 4: calculate_balances_avg.ipynb

Figure 5: SouthTransport_ThroughStraits.ipynb

Figure 6: TransportThroughStraits_Correlations.ipynb

Figure 7: SouthFlow_Comps.ipynb

Figure 8: TransportThroughStraits_Correlations.ipynb

Figure S1: maps_sjgi.ipynb

Figure S2: reflux_SJI_analysis.ipynb

Figure S3: calculate_balances_avg.ipynb

Figure S4: Balances_SupplAnalysis.ipynb

Figure S5: Monthly_CrossSections.ipynb

Figure S6: IntegratedDensity_SuppAnalysis.ipynb

Figure S7: IntegratedDensity_SuppAnalysis.ipynb

Figure S8: SouthFlow_Comps.ipynb

Figure S9:  TransportThroughStraits_Correlations.ipynb

Figure S10: TransportThroughStraits_Correlations.ipynb