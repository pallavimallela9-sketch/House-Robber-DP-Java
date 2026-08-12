# House Robber - Dynamic Programming

## Problem Statement

You are a professional robber planning to rob houses along a street.

Each house contains a certain amount of money.

You cannot rob two adjacent houses because the security system
will be triggered.

Find the maximum amount of money you can rob.

## Example

### Input

[2, 7, 9, 3, 1]

### Output

12

## Explanation

The best choice is to rob:

2 + 9 + 1 = 12

We cannot rob adjacent houses.

Therefore, the maximum amount of money is 12.

## Approach

This problem is solved using Dynamic Programming.

For every house, we have two choices:

1. Skip the current house.
2. Rob the current house and add its money to the amount
   obtained before the previous house.

The formula is:

current = max(previous, previousPrevious + money)

Only two variables are required, so we do not need a separate
DP array.

## Complexity

- Time Complexity: O(n)
- Space Complexity: O(1)

## Language

Java

## Algorithm

Dynamic Programming

## Author

M. Pallavi
