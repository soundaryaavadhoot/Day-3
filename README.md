# Day-3
What is Recursion?
     Recursion occurs when a function calls itself directly or indirectly.
     
For example:
1.Find sum using recursion.
//1,2,3,4,5,6...
//1+2=3
//1+2+3=6
//1+2+3+4=10
int sum(int n)
//4+3+2+1+0
{
 if (n>0) return n+sum(n-1);
 else return 0;
}

2.Find factorial using recursion.
  Basic way to find factorial
  int fact(int n)
  {
    if (n==1)
    return;
    else return (n*fact(n-1));
  }
    
