# TinMEG_MNE

### The code includes multiple sections as following: (just run the parts you need)
1. Loading MEG data and defining events
2. Maxwell filtering and environmental noise recduction
3. Preprocessing of the MEG recordings and saving clean epochs (note that blinks are not removed via ICA)
4. Concatenating, creating evoked objects and grand averaging
5. Check EOG response (recreating of the figure in Niklas thesis)
6. Check ERF response (recreating of the figure in Niklas thesis)
7. Cortical surface reconstruction (+bem, +head_model) with FreeSurfer
8. Morphing to freesurfer template brain
9. Some Visualization examples to check subjects response individually (all subjects * all conditions)
10. Plotting time courses in transverstemporal
11. Statistics (test if the evoked response is significantly different between two conditions across subjects)
12. From source to brain labels in DK atlas
13. Making big dataframe with all information (peak latency, inhibition index, ...)
14. Tinmeg1 plots (paper plots)
15. Tinmeg2 plots (paper plots)
16. Tinmeg3 plots (paper plots)
17. Creating tables (paper tables)

Best,
Payam
