/*
Problem Statement

At the annual meeting of Board of Directors of Acme Inc, every one starts shaking hands with everyone else in the room. Given the fact that any two persons shake hand exactly once, Can you tell the total count of handshakes?

Input Format 
The first line contains the number of test cases T, T lines follow. 
Each line then contains an integer N, the total number of Board of Directors of Acme.

Output Format

Print the number of handshakes for each test-case in a new line.

Constraints

1 <= T <= 1000 
0 < N < 106

*/


#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,T,hs;
    scanf("%d",&T);
    for(;T>0;T--)
        {
        hs=0;
        scanf("%d",&n);
        if(n-1==0 || n==0)
           hs=0;
        else
            {
            for(n=n-1;n>=1;n--)
                hs=hs+n;
        }
        printf("%d\n",hs);
    }

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}

