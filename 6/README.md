```r
x <- c(2, 4, 4, 6, 8)
mean_value <- mean(x)
median_value <- median(x)
mode_value <- as.numeric(names(which.max(table(x))))
cat("Data :", x, "\n")
cat("Mean :", mean_value, "\n")
cat("Median :", median_value, "\n")
cat("Mode :", mode_value, "\n")
