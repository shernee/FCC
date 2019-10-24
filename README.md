# FCC (Federal Communications Commission) Consumer Complaints Analyzer

### This is a project to analyze FCC Consumer Complaints with respect to the service received and issues faced across the United States of America

## Sample Data

To download the original data set directly from the website, the link is:

https://opendata.fcc.gov/Consumer/CGB-Consumer-Complaints-Data/3xyp-aqkj

To plot the US Map, I have used Bokeh sampledata.  (https://docs.bokeh.org/en/1.3.2/docs/reference/command/subcommands/sampledata.html)

The Libraries required to run this project are available in *Requirements.txt*.

## Analysis of Data

The Python code for the Analysis of this dataset is in *Analysis.ipynb*

1. Run the cell to show the usmap plot
2. Use the Hover tool on the Map plot to check out overall percentage of complaints across all States
3. On entering the selected State code (as prompted), a table showing the defective Product/Service and the     corresponding percentage of complaints will appear (in descending order)
4. On entering the (corresponding Index for the) selected Product/Service (as prompted), 3 tables will appear showing highest and lowest percentages of
    * The type of unwanted call/message identified by the consumer
    * The Issue type the consumer is complaining about
    * The specific/particular Issue the consumer is complaining about
    