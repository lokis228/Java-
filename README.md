Массив
Завдання 1

import java.util.Scanner;

public class Test1 {
    public static void main(String[] args) {
        Scanner n = new Scanner(System.in);
        System.out.println("Enter number");
        int N = n.nextInt();
        int[] A = new int[10000];
        for(int i = 0; i < N; i++){
        	Scanner in = new Scanner(System.in);
            System.out.println("Enter number " + i + ":");
            A[i] = in.nextInt();
        };
        for(int i = 0; i < N; i++){
            System.out.printf("%2d", A[i] );
            i+=1;
        };
        
    }
}
 			Завдання 2

import java.util.Scanner;

public class Test2 {
    public static void main(String[] args) {
        Scanner n = new Scanner(System.in);
        System.out.println("Enter number");
        int N = n.nextInt();
        int[] A = new int[10000];
        for(int i = 0; i < N; i++){
        	Scanner in = new Scanner(System.in);
            System.out.println("Enter number " + i + ":");
            A[i] = in.nextInt();
        };
        for(int i = 0; i < N; i++){
        	int m = A[i]%2;
        	if(m==0) {
            System.out.printf("%2d", A[i] );
        	}
        	else;
        	};       
    }
}
 
Завдання 3

import java.util.Scanner;

public class Test3 {
    public static void main(String[] args) {
        Scanner n = new Scanner(System.in);
        System.out.println("Enter number");
        int N = n.nextInt();
        int[] A = new int[10000];
        for(int i = 0; i < N; i++){
        	Scanner in = new Scanner(System.in);
            System.out.println("Enter number " + i + ":");
            A[i] = in.nextInt();
        };
        int k = 0;
        for(int i = 0; i < N; i++){
        	int m = A[i]%2;
        	if(A[i]>0) {
            k +=1;
        	}
        	else;
        	};
        	System.out.println(k);
    }
}
 
Завдання 4

import java.util.Scanner;

public class Test4 {
    public static void main(String[] args) {
        Scanner n = new Scanner(System.in);
        System.out.println("Enter number");
        int N = n.nextInt();
        int[] A = new int[10000];
        for(int i = 0; i < N; i++){
        	Scanner in = new Scanner(System.in);
            System.out.println("Enter number " + i + ":");
            A[i] = in.nextInt();
        };
        int k = 0;
        for(int i = 0; i < N; i++){
        	int m = A[i]%2;
        	if(A[i]<A[i+1]) {
            k +=1;
        	}
        	else;
        	};
        	System.out.println(k);
    }
}
 
Завдання 5

import java.util.Scanner;

public class Test5 {
    public static void main(String[] args) {
        Scanner n = new Scanner(System.in);
        System.out.println("Enter number");
        int N = n.nextInt();
        int[] A = new int[10000];
        for(int i = 0; i < N; i++){
        	Scanner in = new Scanner(System.in);
            System.out.println("Enter number " + i + ":");
            A[i] = in.nextInt();
        };
        int k = 0;
        for(int i = 0; i < N; i++){
        	int m = A[i]%2;
        	if(A[i]<0 && A[i+1]<0) {
            k +=1;
        	}
        	else;
        	};
        	if(k>0){
        	System.out.println("yes");
        	}
        	else {
        		System.out.println("no");
        	};
    }
}
 
