```r
library(readr)
diabetest1 <- read_csv("C:/Users/jaiva/diabetes.csv")
A <- c(diabetest1$Age)
Minimum <- min(diabetest1$Age, na.rm = TRUE)
print(Minimum)
