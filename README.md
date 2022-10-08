# Analyzing-the-ability-to-hold-water
Soil scientists characterize and classify soils into different groups. Each group of soil has 
differing ability to hold water depending on the particles inside. For the sake of simplicity, you 
are given the internal structure of soil as n-by-n grid of cells. Each cell is either 1 or 0. 
• 1 means, the cell allows water to drain. 
• 0 means that cell will hold the water. 
You are asked to write a Java program. The program shall
• Read n-by-n grid of cells from a text file
• Determine if the soil allow the water to drain or hold the water 
o Prints “Allow water to drain” or “Don’t allow water to drain” as a console output.
You are asked to implement and use the Weighted Quick Union with Path Compression unionfind algorithm to solve whether a soil example allows water to drain. You are supposed to build 
your solution on the given partial implementation provided with src.zip file. You are not 
allowed to use union-find implementations provided in alg4.jar.
Sample Input File-1:
1 0 1 0 1
1 1 0 1 0
0 1 1 0 1
1 0 1 0 1
1 0 1 1 1
Sample Output-1:
Allows water to drain
Sample Input File-2:
1 0 0 1 1
0 1 1 1 0
1 0 0 0 1
1 0 0 0 1
1 1 0 1 1
Sample Output-2:
Don’t allow water to drain
Sample Input File-3:
1 0 0 1 1 1 1 0 0 0
0 1 1 1 0 0 0 1 1 0
1 0 0 1 1 0 0 1 0 0
1 0 0 0 1 1 1 0 0 0
1 1 0 1 1 1 1 0 0 0
1 0 1 1 0 1 1 1 1 0
0 0 0 0 1 1 0 0 0 0
1 0 1 1 1 1 1 0 0 0
0 1 0 1 1 0 1 0 1 0
1 1 0 1 0 1 1 0 0 0
Sample Output-3:
Allows water to drain
