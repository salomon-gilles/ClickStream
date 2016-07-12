# Click Stream

This exercise demonstrates using the ggplot package for enhancing visualization. We have a total of 31 dataset files we could use. Download is done dynamically into the memory at run time to ensure no interaction with users local storage. A for loop is used to process all files. To loop through each file, thanks to the naming pattern of the files. We use the current subscript to build the file name which is them appended to the download url: "http://stat.columbia.edu/~rachel/datasets. We then download the file, apply the processing, mainly adding an age group field to the data set, computing the clicks and ggplotting. First, for click impressions and the second time, for click rates. 

Because of the long processing time it may take given the huge number and size of file, I added a break to control what is processed. The default is to run the entire loop. This will take quite some time. If you just wish to process the first dataset only, prepend a # to the break statement.

The final output is a html file.
