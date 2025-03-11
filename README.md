# Big Data Analysis: k-Center Problem with z Outliers

This repository presents a 2-round coreset-based MapReduce algorithm designed to address the k-center problem with z outliers. The k-center problem involves selecting k centers from a set of points to minimize the maximum distance between any point and its nearest center. Introducing z outliers allows for the exclusion of up to z points that do not fit well with any center, enhancing the robustness of the clustering solution.

## Algorithm Overview

The repository implements a two-round coreset-based approach utilizing MapReduce:

1. **First Round**: A coreset is constructed to approximate the original dataset, reducing its size while preserving essential characteristics.
2. **MapReduce Execution**: The coreset is processed using MapReduce to efficiently compute potential centers.
3. **Second Round**: The results from the MapReduce step are refined to identify the final set of k centers, considering up to z outliers.

This methodology leverages the distributed computing power of MapReduce to handle large-scale datasets effectively.


## Acknowledgments

This project was developed as the third assignment for the Big Data Computing course.
