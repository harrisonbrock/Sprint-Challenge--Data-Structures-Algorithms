Exercise I

a. O(n^3)

b. O(lg n)

c. O(8 * n) sqrt(n) / 2 = n

d. O(lg 2)

e. O(n^3)

f. O(n)

g. O(n)


Exercise II
a.
```java
int findMaxDiff(int arr[], int n)    
    {
        if (n < 2)
        {
            System.out.println("Invalid ");
            return 0;
        }

        int min_val = Integer.MAX_VALUE,
            max_val = Integer.MIN_VALUE;
         
        for (int i = 0; i < n; i++)
        {
            if ((arr[i]-i) > max_val)
                max_val = arr[i] - i;
                 
            if ((arr[i]-i) < min_val)
                min_val = arr[i]-i;
        }
 
        return (max_val - min_val);
    }

```

b.

Here we could just use binary search.


Exercise III

a. O(n lg n)
b. O(n^2)