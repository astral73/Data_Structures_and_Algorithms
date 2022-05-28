We will sort this array a = [16,21,11,8,12,22] by using Merge Sort.

Question 1) Write the stages of the above array according to the sort type.

Answer 1)
                                                      16  21  11  8  12  22
                                                      |                   |
                                                      V                   V
                                                 16  21  11            8  12  22
                                                     |                    |
                                                     V                    V
                                                   16 21    11          8 12    22
                                                   |                    |
                                                   V                    V
                                               16   21    11        8   12    22
                                                 \  /     |          \  /     |
                                                  V       V           V       V
                                                16 21     11         8 12     22
                                                  \       /           \       /
                                                      V                   V
                                                   11 16 21            8 12 22
                                                       \                 /
                                                                V
                                                         8 11 12 16 21 22
                                                         
Question 2) Write the big - O notation.

Answer 2) O(n * logn)
