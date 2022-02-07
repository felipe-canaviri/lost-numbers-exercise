# Lost Number - Exercise

## Problem Description - Part I
Given a sequence of string-numbers, from x to N, which could be disordered. This sequence has one missing number, the challenge is to find the missing number.

Examples:
  - Given the array `["13", "11", "9", "10"]`, which sorted is `["9", "10", "11", "13"]`, the method should return `12`.  
  - Given the array `["7", "4", "5"]`, which sorted is `["4", "5", "7"]`, the method should return `6`.  
  - Given the array `[]`, the method should return `0`.  

## Unit Testing
* Create a unit test project with to test the examples above and other scenarios

## Problem Description - Part II
Now the sequence might contain string-expresions (add and subtract) as elements, where the expression will define de number of the element.  

Examples:
  - Given the array `["10 + 3", "12 - 1", "9", "10"]`, which sorted with calculated values is `["9", "10", "11", "13"]`, the method should return `12`.
  
Update your logic for the problem so now it can support string-expressions. Add unit tests for this new requirement.
