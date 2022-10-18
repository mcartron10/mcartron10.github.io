# EDAs

I have yet to regularly conduct formal Exploratory Data Analyses in a professional setting, but I would look to start similarly to that of the recommendation given in the IBM article. The overall goal should be to get a sense of what methods might be appropriate for the given data. Because modeling requires making certain assumptions, it would be best to understand what kind of assumptions can be made before proceeding. A useful analogy might be a visit to the doctor’s office. You might be there for a particular reason, but they will still check other useful metrics as a way to have a more complete picture of the patient, thereby being in the best position to attend to the particular issue. 

In performing an EDA, I would begin by producing summary statistics for each of the variables as a way to investigate them individually. For snapshot comparisons across variables, I am a proponent of matrix visualizations like the scatter plot matrix (see the `pairs()` function from base R along with similar functions like `pairs_panels()`). These visualizations are excellent for examining relationships across multiple variables, as one might want to do from the outset.  These matrices will also render univariate visualizations, which is also useful in examining variables by themselves. 

From the above suggested methods, we should be looking to check assumptions (we can do this in greater detail with diagnostic plots). We should also be looking for patterns—especially anomalies—in the data as these can be problematic when modeling (or may yet tell us something we did not expect and to which we must thus adapt). 
Again, by conducting an EDA from the outset, we give ourselves a better platform from which can begin to investigate the data in more detail and create useful create models. 