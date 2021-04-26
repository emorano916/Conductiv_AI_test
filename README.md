## Description

#### A semiconductor fab is creating thin films with a chemical vapor deposition process.

#### They have completed Design of Experiment on 500 wafers by varying 3 process parameters:

   * Flowfactor: inversely proportional to precursor gas flow.</blockquote>
   * Spacing: distance between shower head that distributes the gas and wafer, in mm.</blockquote>
   * Deposition Time (in seconds).</blockquote>

<i> They chose 125 parameter combinations (recipes) and performed each of them on 4 different tools to account for tool variation.

<i> Film thickness values were measured (in angstrom) at 49 specific points on the wafer (sites). The specification is 1500Å.

<i> Coordinates of the sites are given in a separate file. Values are in micrometers, (0,0) is the center of the wafer.

### Task:
    
   * Build a machine learning model that predicts thickness at each site based on flowfactor, spacing, deposition time, and tool.
    
   *(Bonus) Build a generative model like VAE or GAN that would predict thickness profile for the whole wafer at once. For that you would need to convert site data to images using interpolation. Explain how you would assess the quality of interpolation.
    
   *(Bonus) Ensure that the model is capable of meaningfully extrapolating 1 standard deviation outside of the ranges of parameters present in the data.
    
   *(Bonus) Build a physics-based model (preferably using simulations) for this process that would include temperature.

#### Files ; site_coordinates.csv + test_assignment_sim.csv
