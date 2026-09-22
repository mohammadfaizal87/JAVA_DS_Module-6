# EX 1 You’re creating a health monitoring device which stores several sensor readings in an array. To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.
5. Compare the current element arr[i] with the minimum of the rest and return the smaller value.   

## Program:
```
/*
Program To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.
Developed by: MOHAMMAD FAIZAL SK
RegisterNumber: 212223240092

import java.util.*;

public class Main {
    static int getMin(int[] arr, int i, int n) 
    {
        
        if (i == n - 1)
            return arr[i];
        
        int minRest = getMin(arr, i + 1, n);
        return Math.min(arr[i], minRest);
        
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        for(int i=0; i<n; i++) {
            arr[i] = sc.nextInt();
        }
        System.out.println(getMin(arr, 0, n));
    }
}

*/
```

## Output:

<img width="576" height="303" alt="image" src="https://github.com/user-attachments/assets/3f8f606d-2c09-4be2-bb25-3137c564b823" />


## Result:
Thus the JAVA prograM ti find the minimum value (e.g., lowest heartbeat), implement a recursive method has implemented successfully
