# Golomb-Ruler
Golomb Ruler using Constraint Satisfaction Problem (CSP)

A Golomb Ruler of order M and length L consists of M marks placed at unit intervals (i.e. integer positions) along an imaginary ruler such that the differences in spacing between every pair of marks are all distinct, i.e. no two pairs of marks are the same distance apart. The number of marks on the ruler is its order, and the largest distance between two of its marks is its length.

Implemented a CSP solution to verify whether or not a Golomb ruler of a fixed length L for M marks exists.

If a solution exists for length L, an optimal length ruler is returned, that is one for which no shorter length ruler exists for M marks.

The CSP solution involved the following two methods:
1. Plain Backtracking
2. BT + Forward Checking

The statistics of running the Golomb Ruler is generated in the report.
