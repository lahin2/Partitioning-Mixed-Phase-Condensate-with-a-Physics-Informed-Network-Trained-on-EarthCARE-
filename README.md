Figure 1: EarthCARE ACM-CAP supercooled liquid fraction versus temperature. The black line is the bin-mean SLF; grey shading is the interquartile range. N=1,273,670 cloudy bins from 22.5∘N to 83.0∘N. 
Mean SLF is ice-dominated through most of the mixed-phase window and rises only near 0∘C, where the IQR opens because warm bins mix ice-dominated and liquid-dominated retrievals. 

Figure 2: Mean SLF v. Temperature for the EarthCARE and ERA5 datasets with Interquartile Range (IQR) overlaid. 
The solid blue line is the mean ERA5 SLF per temperature bin; blue shading is the ERA5 IQR. The black line is the bin-mean SLF; grey shading is the EarthCARE IQR.

Figure 3: Champion PINN SLF skill on the EarthCARE test (n=191,047). RMSE, MAE, R2 for all-cloudy, mixed-phase, and ice-only subsets. All-cloudy scores are ice weighted. Ice-only R2 is unmarked as observed SLF is identically zero.

Figure 4: Mean SLF in temperature–latitude bins on the same EarthCARE test. 
(a) EarthCARE ACM-CAP, (b) PINN, (c) PINN - EarthCARE, (d) absolute difference. Bins with fewer than 20 samples are omitted. Panels (a) and (b) are bin means, so they understate pointwise scatter. 
The PINN is slightly too icy; the largest absolute error is near 0∘C. 

Figure 5: Mean SLF from EarthCARE and ERA5 v. Temperature and the average predicted SLF from the PINN per temperature bin and containing mean bias per temperature bin.

Figure 6: PINN versus offline MG1.0 (B2) SLF skill on 32 ERA5 sequences as a function of lead time. (a) RMSE, (b) MAE, (c) bias (predicted - ERA5), (d) R2. Each lead has 5–8 scored cloudy points. Both models have near-zero or negative mean R2 for most of the run. 

Figure 7: PINN versus B2 on ERA5, averaged over leads 20–200 min. (a) SLF RMSE, (b) MAE, (c) bias, for all scored columns and mixed-phase columns. 
The PINN has lower mixed-phase RMSE and a smaller low-liquid bias than B2; both mixed-phase errors remain large.

Figure 8: Model Comparison between a regular data driven MLP and the PINN used in this study. 
The green line represents the performance of the PINN whereas the orange line represents the data only MLP. It is tested on the same ERA5 time series and RMSE and skill is measured. The dotted red line is the average performance of the B2 model.
