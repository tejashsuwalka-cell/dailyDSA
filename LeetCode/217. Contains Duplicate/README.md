# Contains Duplicate

**Difficulty:** Easy  
**Topic:** Array / Hash Set

## What I Did

I used a set to keep track of numbers I had already seen.

As I iterated through the array, I checked whether the current number was already in the set.
If it was, I returned `true` because a duplicate exists.
If it was not, I added it to the set and continued.

## Complexity

Time: `O(n)`  
Space: `O(n)`