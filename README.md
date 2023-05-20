/******************************************************************************

                              Online C++ Compiler.
               Code, Compile, Run and Debug C++ program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <iostream>

using namespace std;

int main()
{   int n;
    cout<<"input the number"<<endl;
    cin>>n;
    
    if (1<=n<=9)
    {
     if (n==1)
     cout<<"one ";
      if (n==2 )
     cout<<"two";
          if (n==3)
     cout<<"three";
          if (n==4)
     cout<<"four";
          if (n==5)
     cout<<"five";
          if (n==6)
     cout<<"six";
           if (n==7)
     cout<<"seven";
          if (n==8)
     cout<<"eight";
          if (n==9)
     cout<<"nine";
    
    }
    else if (n<9)
    
     cout<<"greater than 9";
    
    
    return 0;
}
