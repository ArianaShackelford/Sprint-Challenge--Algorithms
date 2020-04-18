#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) I believe the run time would be `O(n)` because the number of operations would grow proportionatly to the input.


b)  Running the code through as n= 1, 2, and 3 the operations jump from 6, to 15, to 30 and continue getting exponentially larger. That said I believe the run time of this would be `O(n log(n))` , because while the for loop makes it seem like the time complexity would be extremly large, the while statement within it cuts down on the operations.


c) I don't entirely know how to guage the time complexity with recursive functions, however this function while it is more scalable than the last one it has a pretty steady increase in operations and for that reason I would say that the run time would be `O(n)`

## Exercise II
I think the most logical aproach for this is problem would be to use binary search, because it's a building the floors are already sorted so it can be used here.
because this is using a binary sort the time complexity would be `O(log(n)`

while the number of floors being tested are > 1:
    start on the middle floor and drop and egg from there,
        if it breaks:
            set the mid point as the new high
            repeat
        elif it doesn't break:
            set the mid point as the new low
            repeat
        else:
            return floor
