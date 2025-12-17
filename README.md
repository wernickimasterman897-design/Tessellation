# Tessellation
A Tessellation Studio's Public Code Repository
This program was written by the author (who is not a computer science major) to demonstrate that, under a specific structure, hexagonal tilings that can cover at least two concentric layers around an initial central hexagon must belong to the three types proposed by Reinhart. Due to the author's limited programming experience, the code formatting and naming conventions may not be rigorous, and updates will be made in the future to improve the structure.

The program is built on the SageMath software. Please first download SageMath (version 9.3 or above) from the official SageMath website, and then open this program in notebook mode. The program mainly illustrates the general approach to hexagonal tiling:

The first code block corresponds to testing the first layer of hexagonal tiling. It filters the possibilities using the equivalent matrix representations of Reinhart's three hexagon types, resulting in 8,010 tiling patterns, which are then classified based on the rank of their equivalent matrices.

The second code block further filters the remaining patterns based on geometric proofs of whether the hexagons corresponding to the 8,010 first-layer tilings belong to Reinhart's three types. This step leaves 384 tiling patterns.

The third code block tests the second layer of tiling for the remaining 384 patterns and displays the results at each step. It is found that all patterns fail at the fourth step (meaning no non-Reinhart hexagon can tile two full layers).

Users only need to open the program and press the run button three times to execute the three code blocks in sequence, which will yield the desired results. Further optimizations of the program are planned. For related questions, please leave a comment or contact the author.
