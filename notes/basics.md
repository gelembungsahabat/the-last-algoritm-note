# Time and Space. Big O as they call it.
## What is Big O
Big O is a way to categorize your algorithms time or memory requirements based on input. It is not meant to be an exact measurement. It will not tell you how many CPU cycles it takes, instead it is meant to generalize the growth of your algorithm.

Example: <br>
So when someone says Oh of N, they mean your algorithm will grow linearily based on input.

## Important concepts
1. growth is with respect to the input
2. Constants are dropped: O(2N) -> O(N) and this makes sense. That is because Big O is meant to describe the upper bound of the algorithm (the growth of the algorithm). The constant eventually becomes irrelevant.
3. Worst case is usually the way we measure


Take the following:

N = 1, O(10N) = 10, O(N^2) = 1


N = 5, O(10N) = 50, O(N^2) = 25


N = 100, O(10N) = 1,000, O(N^2) = 10,000 // 10x bigger


N = 1000, O(10N) = 10,000, O(N^2) = 1,000,000 // 100x bigger


N = 10000, O(10N) = 100,000, O(N^2) = 100,000,000 // 1000x bigger

