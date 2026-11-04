```r
library(readr)
diabetest1 <- read_csv("C:/Users/jaiva/diabetes.csv")
A <- c(diabetest1$Age)
Mean <- mean(A, na.rm = TRUE)
Std <- sd(A, na.rm = TRUE)
Zscore <- (A - Mean) / Std
Std
