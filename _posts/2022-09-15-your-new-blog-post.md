## Project 1 Reflection

Link to project [here](https://mcartron10.github.io/Stat558_Project1_CartronMatthieu.html)

Project one--the first project of Stat 558--concerned data processing, or getting data into a form such that it can be analyzed. From what I have heard and experienced professionally, this is often the most strenuous part of the modeling process. Data rarely appears in the structured, readable form that we have come to associate with various library data sets. This is why the processing stage is so vital, even if it is at times tedious and onerous. 

But there is also great satisfaction in creating solutions that work. For project one, we initially processed the given raw data function by function (base R and tidyverse) which worked fine, but remains rather inflexible and inconvenient, especially if that process must be repeated. 

To save time (not to mention reducing the number of lines of code), you can create generic functions. We can nest the built-in functions into these generic functions and vastly reduce the number of functions through which we pass the original data files. 

The project instructions had us create these generic functions and additionally create generic functions to plot the various tibbles. The flexibility that generic functions provide was especially on display here: secondary arguments allowed for the customization of plots (as well as for our data processing, though to a lesser degree) so that the resulting visualization were better tailored toward our needs. For the particular census data we used, we could zero in on particular counties and states with these secondary arguments, which would have been more difficult to achieve otherwise.

Much of what we practiced was new for me. I do not have a computer science background and have little experience with writing my own functions. I have only ever really used built-in functions sequentially, and while writing functions for this assignment was difficult, I was able to see its advantages. 

Reflecting on the project, there is certainly one thing I would like to improve upon to bolster my function writing skills: improving my understanding of the interactions between various environments (global, function, etc.). I found myself often making the extra effort to give object names within functions completely unique names (that I had not used in the global environment or in a previous function) so that there could never be any confusion within the program as to which object I was specifying. With more practice and knowledge on this front I think I could get more comfortable, and the result would be code that is a little easier to read! 
