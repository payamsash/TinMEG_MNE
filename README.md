# TinMEG
## Analysing and preprocessing of MEG + MRI data

Inhibitory mechanisms in sensory gating has been traditionally measured in humans by means of startling blinking responses, being partially suppressed by preceding and weaker lead stimuli. Paradigms such as pre-pulse inhibition (PPI) have been used for near half a century as a means to diagnose psychiatric disorders in which disrupted PPI is a surrogate for altered sensory gating in schizophrenia. However, the electrooculographic (EOG) response is very variable and some individuals do not blink, making it a poor outcome measure at the individual level. Unlike PPI, which is regulated in the lateral globus pallidus from the basal ganglia, inhibition of the startle reflex by preceding silent gaps embedded in a continuous background noise is processed in the auditory cortex, making it particularly suitable for measuring cortical responses. Here, based on the behavioral Gap-Pre-pulse Inhibition of Acoustic Startle (GPIAS) stemming from animal research, we present a new paradigm using source localized magnetoencephalography (MEG) in 22 normal hearing healthy participants. We evidence a near 72.5% (±15.9%) suppression of N1 evoked response to a pulse as high as 90 dB(A) sound pressure level (SPL) when preceded by a 50 ms long silent gap in a 60 dB(A) SPL broadband carrier noise. Cortical inhibition was greatest with 240 ms time intervals between gap and pulses, and about 1.5 times larger in the right transverse temporal gyrus when compared to the left hemisphere. While merely 23% of the individuals blinked at the highest pulse levels, cortical evoked responses were found in all participants. Overall, we provide evidence that the N1 cortical response to sound
pulses is reliably inhibited by preceding gaps. We propose this paradigm as an effective method to assess auditory sensory gating through development and aging, and
potentially as a method for the diagnosis of hearing disorders like tinnitus or hyperacusis.

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
14. Performing Statistical tests on the results
15. Plotting (paper plots)
17. Creating tables (paper tables)
