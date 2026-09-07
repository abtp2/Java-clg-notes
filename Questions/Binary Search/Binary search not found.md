# Question
Given a sorted integer array and a target value, implement Binary Search and print "Not Found" if the target does not exist.

```cpp
#include<iostream>
using namespace std;

int main(){
  int arr[] = {1,2,3,4,5,6,7,8};
  int target = 6;
  int n = sizeof(arr)/sizeof(arr[0]);
  int left=0, right=n-1, mid;
  while(left<=right){
    mid = (left+right)/2;
    if(arr[mid]==target) return mid;
    else if(arr[mid]>target) right=mid-1;
    else left=mid+1;
  }
  cout << "Not Found";
  return 0;
}
```