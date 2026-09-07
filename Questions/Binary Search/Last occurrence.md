# Question
Given a sorted array containing duplicate values, use Binary Search to find the last occurrence of a given target.

```cpp
#include<iostream>
using namespace std;

int main(){
  int arr[] = {1,3,4,4,5,5,5,6,7,8,8,8};
  int target = 5;
  int n = sizeof(arr)/sizeof(arr[0]);
  int index = -1;
  int left=0, right=n-1, mid;
  while(left<=right){
    mid = (left+right)/2;
    if(arr[mid]==target){
      index = mid;
      left = mid+1;
    };
    else if(arr[mid]>target) right=mid-1;
    else left=mid+1;
  }
  cout << index;
  return 0;
}
```