In this project we analyses DNA reads to identify mutations and compare mismatch patterns between control and treatment samples.
The code is aimed to validates reads, identifies mutations, summarises mismatch frequencies and compares groups using Welch's t-test.

3 tests were used:
-Normal input, which checked mismatch counts and positions.
-Empty input, which checked empty return values.
-Invalid reads, which checked exclusion of samples with no valid reads.
Results:
Treatment samples showed higher mismatch frequencies and position 97 showed a significant difference between groups (t = 14.08, p = 0.00496).
