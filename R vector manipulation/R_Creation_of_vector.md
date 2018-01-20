R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](R_Creation_of_vector_files/figure-markdown_strict/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

    # Creation of a vector
    sha <- c(3,5,2,7,9,12,15,18,20,25)

max(sha) \# find max value in vector min(sha) \# find min value in
vector range(sha) \# find range of a vector sum(sha) \# find sum value
in vector length(sha) \# find length of the vector Mean\_sha =
sum(sha)/10 sha+2 sha\*2 sha^2 sha\[3\] \#third element in a vector
sha\[4:8\] \# fourth to eighth element in a vector sha\[-1\] \# Drop the
first element in a vector sha\[-3\] sha\[-length(sha)\] \#Drop the last
element of the vector sha ssv &lt;- c(1,2,3,4,5,6,7,8,9,10)\#
concatenate sha and ssv sha\_ssv &lt;- c(sha,ssv) sha\_ssv
