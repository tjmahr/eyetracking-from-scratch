# eyetracking-from-scratch

main steps:

- collecting data (your job)
- reading in data
- time-locking
- mapping to AOIs
- interpolating/deblinking
- classifying trials by location at a given time
- this is the dataset! store it.
- aggregating looks
- modeling: gca, splines, nonlinear regression
- miscellany

reading in data

- let's assume bare minimum
  - one row per time sample with gaze coordinates for each eye
  - eyelink might not give this? (never used it)
- what do we have
  - screen proportions? pixels?
- where is the origin
  - screens put 0,0 in upper left corner because cathode ray guns. decartes put 0,0 in bottom-left
- normalize origin and pixels
- offscreen looks?
  - just set them to NA
- monocular averaging
  - eye-dentification problems
  - read the manual: do they include quality/reliability measures for each sample?
- let's make a plot

 
databasing eyetracking data

- experiment features / experiment administrations / trials / looks
- participants
- other tables to link to participants

miscellany

- visual angles, finding saccades, smoothing data
- clean reaction times are so uncommon what do they even measure
- coded videos
  - 30 frames per second
  - where is left?
- let the light in: pupillometry 
 
