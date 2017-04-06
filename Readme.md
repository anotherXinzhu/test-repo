# First we need to download the zip file into the working directory

fileUrl<-"https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
download.file(fileUrl,destfile = "data.zip",method="curl")
unzip("data.zip")

# To make things easier, we can set data folder named "UCI HAR Dataset" as our working directory. 
setwd("UCI HAR Dataset" )  
