# Burrows-Wheeler-Algorithm
The combination of Burrows-Wheeler Transform, MTF(Move to Front), Huffman Code. 
For example, S = "abraca"
first, 0 abraca
       1 bracaa
       2 racaab
       3 acaabr
       4 caabra
       5 aabrac
     
after sorting,
       0 aabra c
       1 abrac a
       2 acaab r
       3 braca a
       4 caabr a
       5 racaa b
       
       next[] = {}
       x = 1;
       
 get the last column, T = "caraab"
