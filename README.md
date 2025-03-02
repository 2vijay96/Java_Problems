Teena is fond of patterns, but she needs your help to solve the below pattern. Given n as input, teena wants you to print the below pattern.

Input Format

n = 5

Constraints

1<=n<=100

Output Format

12345
678910
1112131415
1617181920
2122232425
Sample Input 0

3
Sample Output 0

123
456
789

Code : 

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();
        scanner.close();
        
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= n; j++) {
                if (j < i) {
                    System.out.print(i);
                } else {
                    System.out.print(j);
                }
            }
            System.out.println();
        }
    }
}
