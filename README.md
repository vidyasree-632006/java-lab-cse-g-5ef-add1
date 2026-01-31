# java-lab-cse-g-5ef-add1
ADDITIONAL EXPERIMENT -1
## additional experiment -1 
# program to insert into a given mainstring from a given position 
source code 
JAVA  
```
import java.util.Scanner;

class InsertSubstring {
    public static void main(String[] args) {
        String mainStr, subStr, result;
        int position;

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the main string: ");
        mainStr = sc.nextLine();

        System.out.print("Enter the substring to insert: ");
        subStr = sc.nextLine();

        System.out.print("Enter the position: ");
        position = sc.nextInt();


        result = mainStr.substring(0, position)
               + subStr
               + mainStr.substring(position);

        System.out.println("Resulting String: " + result);
    }
}


```
# OUTPUT : 
![OUTPUT  OF ADDITIONAL EXPERIMENT 1](ADD1.png)
