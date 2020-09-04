
##### Task 1

Downlod file

```r
url<-"https://data.gov.ua/dataset/175386f8-fbce-4352-8ec9-44fc8c436aa9/resource/e58e005a-c448-4d97-9d45-813f05b1d737/download/nabir-2020-2022-roki.xls"
download.file(url, destfile="./forecast.xlsx", mode='wb')
```

Read file

```r
install.packages("readxl")
library(readxl)
read_excel("C:/Users/HP/Documents/forecast.xls", sheet=1)
```

##### Task 2
Download file
```r
fileurl<-("https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Fss06hid.csv")
download.file(fileurl, destfile="./getdata.csv", mode='wb')
```

read csv file
```r
fileUrl <- "https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Fss06hid.csv"
df <- read.csv(fileUrl)
df
```