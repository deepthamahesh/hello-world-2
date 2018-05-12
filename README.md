# hello-world-2
FINAL
DEEPTHA MAHESH 110117050
I am **Deeptha Mahesh** 
I study B tech ICE 1st year at *NITT*
My hometown is ***Chennai***


**I am Deeptha Mahesh**
I study Btech *ICE* 1st year at *NITT*
My hometown is **Chennai**




#include<iostream.h>
#include<conio.h>

void sort(int A[20], int n)
{ int t;
  for( int i=0; i<n-1;i++)
  for( int j=0;j<n-i-1;j++)
  if(A[j]>A[j+1])
  { t=A[j];
    A[j]=A[j+1];
    A[j+1]=t;
  }
}
void main()
{ clrscr();
  int A[20],n,i;
  cout<<"\t\tBUBBLE SORTING.\n\n";
  cout<<"Enter the size of the array:";
  cin>>n;
  cout<<"\nEnter the array to be sorted:\n";

  for(i=0;i<n;i++)
  cin>>A[i];
  sort(A,n);
  cout<<"\n The sorted array is : ";
  for(i=0;i<n;i++)
  cout<<A[i]<<"\t";
  getch();

 }


