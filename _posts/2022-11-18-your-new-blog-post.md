# Project 3 Reflection

Our project consisted of six automated reports featuring each of the six data channels of article genres—business, entertainment, lifestyle, world news, social media and technology—from the UCI Machine Learning News Popularity data set. In each report we conducted an exploratory data analysis and subsequently built predictive models in order to see if we could predict the number of times an article was shared.  

This project posed a number of new challenges. Because each report was automated, we had to curtail our code to this automation, that is, we could not include information that might be so specific that it might work for one data channel but not for the others. We picked what we thought were interesting variables to compare with the share variables in the EDA, and afterward automated comparisons using correlation thresholds. This allowed to try and retain some specificity and insight without catering the analysis to one data channel over others. 

Similarly, we had to find a way to automate our models so that each might provide some insight all the while making sure that the models worked for each channel. For feature selection, for example, we performed a Principle Components Analysis to reduce the dimension of the predictor set of variables (there were quite a few). Aspects of the EDA as well as the model selection and training will thus be different depending on the data channel, but the analysis for each should still be valid. And that was ultimately the goal; to use automation, something that can be constricting initially, on an analysis that we still wanted to be broad enough to cover all of the different data channels and the relationships between variables contained therein. 

What would I do differently if I were to do it all again? Unfortunately, during the critical last few days of the project, I lost a member of my family, making the completion of my assigned duties more difficult. Given what happened, I am proud of what I was still able to accomplish. Sneja was accommodating and patient too, which also really helped. I think, with more time, I would have liked to have worked more on the more intricate and complex aspects of the automation. This was certainly the most difficult part of the project for me. I feel, however, that I made progress in this area, especially as I look back on my R programming abilities at the start of the semester (and even just a few weeks ago!). I learned a lot from my partner’s strengths—especially in this area—and I will certainly look to implement my new knowledge, where possible, in the future. 

The biggest takeaway from this project was yet another glimpse into the sheer expansiveness of R and programming in general. More practice with predictive models was extremely useful, but learning to think about automating all of the analysis pushed me to think in a way that I rarely have had to. How could we discuss and analyze the data channels (and models) in a meaningful way without actually setting aside specific points and details for each analysis? This was eye-opening, and begins to make you think about all of the doors automation opens up, even beyond the world of statistics and machine learning. 

Below you can find useful links relating to the project: 


- Link to the project repository [here](https://github.com/mcartron10/Stat558_Project3_CartronKaranjai)

- Link to the project site [here](https://mcartron10.github.io/Stat558_Project3_CartronKaranjai/)
