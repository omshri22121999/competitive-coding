# Unit GCD

Chef has a recipe book. He wishes to read it completely as soon as possible so that he could try to cook the dishes mentioned in the book.

The pages of the book are numbered 1 through N. Over a series of days, Chef wants to read each page. On each day, Chef can choose to read any set of pages such that there is no prime that divides the numbers of two or more of these pages, i.e. the numbers of pages he reads on the same day must be pairwise coprime. For example, Chef can read pages 1, 3 and 10 on one day, since (1,3), (3,10) and (1,10) are pairs of coprime integers; however, he cannot read pages 1, 3 and 6 on one day, as 3 and 6 are both divisible by 3. Since the recipes are really interesting, Chef does not mind reading pages more than once.

Given N, determine the minimum number of days Chef needs to read the entire book and the pages Chef should read on each of these days.

## Input

- The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
- The first and only line of each test case contains a single integer N.

## Output

For each test case:

First, print a line containing a single integer D ― the minimum number of days required to read the book. Let's number these days 1 through D.
Then, print D lines describing the pages Chef should read. For each valid i, the i-th of these lines should contain an integer Ci followed by a space and Ci space-separated integers ― the numbers of pages Chef should read on the i-th day.
If there are multiple solutions with the minimum number of days, you may print any one.

## Example Input

```
1
5
```

## Example Output

```
2
3 1 2 5
2 3 4
```