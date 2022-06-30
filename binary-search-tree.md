[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

                7
              /   \
             5     8
            / \     \ 
           1   6     9
          / \
         0   3
            / \
           2   4
           
# Example
Root -> 7, target = 2

1 -> target < 7, go left

2 -> target < 5, go left

3 -> target > 1, go right

4 -> target < 3, go left

5 -> target = 2, DONE

