# Arrays left rotation
Code challenge: Given an array α of η integers and a number, d, perform d left rotations
A _left rotation_ operation on an array shifts each of the array's elements **1** unit to the left. For example, if **2** left rotations are performed on array **\[1, 2, 3, 4, 5\]**, then the array would become **\[3, 4, 5, 1, 2\]**. Note that the lowest index item moves to the highest index in a rotation. This is called a _circular array_.

Given an array **α** of **η** integers and a number, **_d_**, perform _**d**_ left rotations on the array. Return the updated array to be printed as a single line of space-separated integers.

**Function Description**

Complete the function _rotLeft_ in the editor below.

rotLeft has the following parameter(s):

*   _int a\[n\]:_ the array to rotate
*   _int d:_ the number of rotations

**Returns**

*   _int a'\[n\]:_ the rotated array

**Input Format**

The first line contains two space-separated integers **η** and _**d**_ , the size of **α** and the number of left rotations.  
The second line contains **η** space-separated integers, each an **α\[i\]**.

**Constraints**

*   1  ≤ **η** ≤ 10^5
*   1  ≤ **d** ≤ η
*   1  ≤ **α\[i\]** ≤ 10^6

**Sample Input**

    5 4
    1 2 3 4 5
    

**Sample Output**

    5 1 2 3 4
    

**Explanation**

When we perform **d = 4** left rotations, the array undergoes the following sequence of changes:

 **\[1, 2, 3, 4, 5\] → \[2, 3, 4, 5, 1\] →\[3, 4, 5, 1, 2\] →\[4, 5, 1, 2, 3\] →\[5, 1, 2, 3, 4\]**
