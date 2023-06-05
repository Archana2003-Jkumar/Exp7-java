# Exp7-java
Aim:
To code a program that adds a new value to an array.
## Algorithm:
### Step1:
Import the required packages.
### Step2:
Using for loop add a new value to the existing array by assigning it to a variable.
### Step3:
 Display the result.

## Code:
```
import java.util.Arrays;
public class Exp7 {


        public static void main(String[] args) {
             int arr[] = {2,4,6,8};
            int n = arr.length;
            int newArr[] = new int[n+1];
            int value = 10;
            System.out.println(Arrays.toString(arr));
            for(int i = 0; i<n; i++) {
                newArr[i] = arr[i];
            }
            newArr[n] = value;
            System.out.println(Arrays.toString(newArr));
        }
    }

```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp7-java/assets/93427594/de14a76e-6ddb-4810-8c72-340c4da3ffb6)

## Result:
Hence the program has been successfully executed.
