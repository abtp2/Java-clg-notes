# Question
Given a sorted integer array and a target value, find the index of the target using Binary Search.


```cpp
#include<iostream>
using namespace std;

int main(){
  int arr[] = {1,2,3,4,5,6,7,8};
  int target = 6;
  int n = sizeof(arr)/sizeof(arr[0]);
  int left=0, right=n-1;
  while(left<=right){
    mid = (left+right)/2;
    if(arr[mid]==target) return mid;
    else if(arr[mid]>target) right=mid-1;
    else left=mid+1;
  }
  return 0;
}
```