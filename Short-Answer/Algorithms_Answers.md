#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The time complexity is O(n). That's because the number of times the loop runs is linearly related to the size of n. If n is 5, then the loop runs 5 times.

b) The time complexity is O(n^2). That's because the size of n impacts two loops, one nested inside of another.

c) The time complexity is O(n). The number of times this recursive function runs is linearly related to the size of n. If n is 5, the loop runs 5 times.

## Exercise II

My strategy is to use a binary search to find f. I would take the height of the building in stories, divide it in 2, go to that floor and throw down an egg. If the egg broke, then I'd check one floor down to see if i was currently at f. If the floor below me also broke i'm not at f. So I'd go to the middle of the bottom half and try again. I'd do this over and over, cutting off half of the height until I found f.

The runtime complexity would be O(log(n)). It's less than O(n) because i'm not checking every floor.
