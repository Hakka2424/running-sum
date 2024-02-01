# Running Sum of 1D Array

This Java program calculates the running sum of a one-dimensional array of integers.

## How to Use

1. **Clone the Repository:**

2. **Compile the Code:**

3. **Run the Program:**

## Implementation Details

- The `Solution` class contains a method `runningSum` which takes an array of integers as input and returns an array of running sums of the original array.
- The running sum of an array `nums` is calculated such that `runningSumArray[i] = nums[0] + nums[1] + ... + nums[i]`.
- If the input array is `null` or empty, the program returns an empty array.

## Example

```java
public static void main(String[] args) {
 Solution solution = new Solution();
 int[] nums = {1, 2, 3, 4};
 int[] result = solution.runningSum(nums);
 for (int num : result) {
     System.out.println(num);
 }
}

Output:
1
3
6
10

Expected Ouput:
[1,3,6,10]
